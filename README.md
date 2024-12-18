## Track your work in a secured way
- 2 Factor Authentication Enables
- Easy to add/remove items

## Installation and Setup

Follow these steps to run the Todo app locally:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/hamitsehjal/LaravelApp_2Factor_Auth
    cd LaravelApp_2Factor_Auth
    ```

2. **Install PHP dependencies using Composer**:
    ```bash
    composer install
    ```

3. **Install JavaScript dependencies using NPM**:
    ```bash
    npm install
    ```

4. **Copy `.env.example` to `.env` and configure your environment variables**:
    ```bash
    cp .env.example .env
    ```
    - Set your database credentials in the `.env` file.

5. **Generate an application key**:
    ```bash
    php artisan key:generate
    ```

6. **Run database migrations**:
    ```bash
    php artisan migrate
    ```

7. **Build frontend assets**:
    ```bash
    npm run dev
    ```

8. **Start the development server**:
    ```bash
    php artisan serve
    ```

9. **Access the application**:

    Open your browser and navigate to `http://localhost:8000`.
