# Homes Booking Demo

A demo Angular application for booking homes, using a mock backend.

## Tech Stack

- [Angular](https://angular.io/)
- [TypeScript](https://www.typescriptlang.org/)
- [JSON Server](https://github.com/typicode/json-server) — mock REST API

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/astkhov/homes-booking-demo.git
   cd homes-booking-demo
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Start JSON Server:**

   ```bash
   npx json-server --watch db.json
   ```

4. **Start Angular development server:**

   ```bash
   ng serve
   ```

5. **Open in browser:**

   Navigate to [http://localhost:4200](http://localhost:4200)

## Project Structure

- `src/` — Angular source code
- `db.json` — mock data for JSON Server
- `angular.json`, `tsconfig.json` — configuration files

## License

[MIT](LICENSE)
