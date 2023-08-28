# Campus Recruitment Drive with RapidFort

Welcome to **RapidFort**, the ultimate solution for campus recruitment drives. RapidFort brings you a cutting-edge web application, backed by a robust REST API-based web server, facilitating seamless file uploads and efficient retrieval of file information. This README provides you with comprehensive insights into the features, usage guidelines, and technical intricacies of the RapidFort project.

## Key Features

- **Effortless File Uploads:** Our user-friendly interface empowers users to effortlessly upload files with ease.
- **File Insights at Your Fingertips:** RapidFort enables users to instantly access detailed information about uploaded files, including essential attributes like file name and size.
- **Intuitive UI:** Experience a simplistic yet engaging web page designed for enhanced user interaction.
- **Empowered by Docker:** Embrace the power of Docker containerization for swift and hassle-free deployment.
- **Seamless Kubernetes Integration:** Leverage the provided Kubernetes manifest files to orchestrate flawless web server hosting.

## How to Use RapidFort

### Local Deployment Instructions

1. Begin by cloning the repository from our trusted source on GitHub.
2. Navigate to the root directory of the project.
3. Install the required Python packages by executing the command.
4. Launch the Flask application by running a command.
5. Access the RapidFort application through your preferred web browser using the link `http://127.0.0.1:5000/`.

### Uploading Files with Ease

1. Launch RapidFort in your web browser.
2. Initiate the file upload process by clicking on the "Upload File" button.
3. Select the desired file from your local system and confirm the upload by clicking "Upload."
4. A prompt will notify you upon the successful completion of the file upload.

### Retrieving Precise File Information

1. Navigate to RapidFort's main page.
2. Click on the "Get File Info" button.
3. Choose a file from your system and proceed by clicking "Get Info."
4. RapidFort will promptly present comprehensive information about the file, including its name, size in bytes, and human-readable size.

## API Overview

### `GET /`

- Access the main page of the RapidFort application.

### `POST /upload`

- Endpoint designed for hassle-free file uploads.
- Submit your file using the `file` parameter in your request.
- Receive a well-defined JSON response indicating the status of your file upload.

### `POST /get_file_info`

- Endpoint exclusively for retrieving meticulous file details.
- Provide a file using the `file` parameter in your request.
- Receive a structured JSON response containing in-depth file information.

## The Inner Workings

### Project Structure

- `app.py`: The heart of the application, containing robust Flask routes and intricate logic.
- `templates/`: Home to meticulously crafted HTML templates ensuring a seamless user experience.
- `uploads/`: The secure vault for safeguarding all uploaded files.
- `Dockerfile`: Crafted Docker configuration pivotal for containerization.
- `deployment.yaml` and `service.yaml`: Inclusion of Kubernetes manifest files, paving the path for deployment.

### Dependencies

- Flask: The backbone of micro web frameworks, serving as the foundation for building web applications.
- Docker: The game-changer, orchestrating application containerization with unparalleled efficiency.

## Embrace the Future with RapidFort

RapidFort seamlessly streamlines the process of uploading and retrieving files, revolutionizing campus recruitment drives. Backed by an intuitive interface, REST API endpoints, and the power of Docker and Kubernetes, RapidFort empowers users to effortlessly manage their files.

For inquiries or assistance, kindly reach out to our dedicated project maintainers or utilize our GitHub repository's issue submission feature.

Dive into the future of file management with RapidFort!
