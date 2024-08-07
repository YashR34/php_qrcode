# PHP QR Code Generator

This project is a PHP-based QR code generator that allows users to generate various types of QR codes by filling out a form. To make your own QR generator, you need to download the `phpqrcode` library. If the QR code is not generating, you may need to enable the GD extension in the XAMPP MySQL configuration.

## Features

- Generate QR codes for different types of data
- Simple and user-friendly form
- Downloadable QR codes

## Technologies Used

- HTML
- CSS
- PHP
- phpqrcode library

## Getting Started

### Prerequisites

- XAMPP or any other PHP development environment
- Git

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/YashR34/php_qrcode.git
    cd php_qr_generator
    ```

2. Move the project files to your XAMPP htdocs directory:
    ```sh
    mv php_qr_generator /path/to/xampp/htdocs/qr_generator
    ```

3. Download the `phpqrcode` library:
    ```sh
    git clone https://github.com/t0k4rt/phpqrcode.git
    ```

4. Copy the `phpqrcode` library to your project directory:
    ```sh
    cp -r phpqrcode /path/to/xampp/htdocs/qrcode/phpqrcode
    ```

5. Ensure the GD extension is enabled in your XAMPP configuration:
    - Open `php.ini` file (located in the `php` folder of your XAMPP installation directory).
    - Find the line `;extension=gd` and remove the semicolon to enable the GD extension.
    - Restart Apache from the XAMPP control panel.

6. Start XAMPP and ensure Apache is running.

7. Access the QR generator by navigating to:
    ```
    http://localhost/qrcode
    ```

## Usage

- Fill out the form with the desired data to generate a QR code.
- Click the generate button to create the QR code.
- Download the generated QR code.

## Contributing

1. Fork the repository.
2. Create your feature branch:
    ```sh
    git checkout -b feature/your-feature
    ```
3. Commit your changes:
    ```sh
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```sh
    git push origin feature/your-feature
    ```
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please contact [YashR34](https://github.com/YashR34).
