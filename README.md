# **secureRealTimeMultiplayerGame**

A secure real-time multiplayer game where players can move avatars, collect items, and compete for rankings based on scores. The application is designed with robust security measures to ensure a safe gaming environment.

---

## **Features**
- Real-time multiplayer functionality using WebSockets.
- Players can control avatars and collect items for points.
- Leaderboard ranks players based on their scores.
- Secure headers to prevent information leakage and ensure data integrity.

---

## **Security Measures**
- **Custom Headers**: The server responds with `X-Powered-By: PHP 7.4.3` to obscure backend technology.
- **XSS Protection**: All inputs are sanitized, and headers are set to mitigate cross-site scripting attacks.
- **MIME Type Sniffing Prevention**: Ensures files are served with correct MIME types.
- **No Caching**: Prevents caching to protect sensitive data.
- Security implemented using `helmet@^3.21.3`.

---

## **Installation**

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Azaam86msn/secureRealTimeMultiplayerGame.git
   cd secureRealTimeMultiplayerGame
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Run the server**:
   ```bash
   npm start
   ```

4. **Access the game**:
   Open your browser and navigate to [http://localhost:3000](http://localhost:3000).

---

## **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
