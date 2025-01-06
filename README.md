# Chatterly

Chatterly is a real-time chat application built with React and Stream Chat, featuring an AI chatbot integration.

## Features

- Real-time messaging
- Channel creation and management
- User authentication
- AI chatbot integration
- Modern, responsive UI
- Team collaboration support

## Prerequisites

Before you begin, ensure you have installed:
- [Node.js](https://nodejs.org/) (version >= 14.0.0)
- [npm](https://www.npmjs.com/) (comes with Node.js)

## Getting Started

1. **Clone the Repository**
   ```bash
   git clone https://github.com/ThienLuong1101/Chatterly.git
   cd Chatterly
   ```

2. **Environment Setup**
   - Create a `.env` file in the root directory
   - Add your Stream API key:
     ```
     REACT_APP_STREAM_API_KEY=your_api_key_here
     ```

3. **Install Dependencies**
   ```bash
   npm install
   ```

4. **Start Development Server**
   ```bash
   npm start
   ```
   This will launch the application at `http://localhost:3000`

## Building for Production

To create a production build:
```bash
npm run build
```

The optimized build will be created in the `build` directory.

## Project Structure

```
chatterly/
├── public/
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── ChannelContainer/
│   │   ├── ChannelListContainer/
│   │   ├── Auth/
│   │   └── Chatbot/
│   ├── App.jsx
│   └── index.js
├── .env
├── .gitignore
└── package.json
```

## Tech Stack

- React.js
- Stream Chat API
- Universal Cookie
- React Router
- CSS3

## Development Guidelines

### Environment Variables
The project uses environment variables for configuration. Required variables:
- `REACT_APP_STREAM_API_KEY`: Your Stream Chat API key

### Git Ignore
The project includes a `.gitignore` file to exclude:
- Dependencies (`/node_modules`)
- Build files (`/build`)
- Environment files (`.env`, `.env.local`, etc.)
- System files (`.DS_Store`)
- Debug logs

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit changes (`git commit -m 'Add YourFeature'`)
4. Push to branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## Troubleshooting

Common issues and solutions:

1. **API Key Not Found**
   - Ensure `.env` file exists in root directory
   - Verify environment variable starts with `REACT_APP_`
   - Restart development server after modifying `.env`

2. **Build Errors**
   - Clear npm cache: `npm cache clean --force`
   - Delete `node_modules` and run `npm install`

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) file for details.

## Contact

Thien Luong - [GitHub Profile](https://github.com/ThienLuong1101)

Project Link: [https://github.com/ThienLuong1101/Chatterly](https://github.com/ThienLuong1101/Chatterly)
