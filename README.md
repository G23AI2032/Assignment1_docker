# Assignment1_docker
Step 1: Deploy a sample web application using docker containers by creating docker images from scratch. Existing docker container images are not allowed.  Step 2: Create a readme file with full explanation of the process followed, describe the app functionality, include details of author (G23AI2032).

# Employee_Feedback_form

The functionality for an employee feedback form in a web application, including fields for first name, last name, email, and message:
Input Fields:
First Name: Allow employees to input their first name.
Last Name: Provide a field for employees to enter their last name.
Email: Include a field for employees to input their email address.
Message: Provide a text area where employees can enter their feedback message.
Included a "Submit" button at the bottom of the form for employees to finalize and send their feedback.

Provide a backend interface for administrators to view and manage feedback submissions, including filtering, sorting, and responding to feedback.
By implementing these functionalities, you can create a user-friendly and effective employee feedback form in your web application, promoting transparency and communication within your organization.

## Table of Contents

- [Docker Installation](#dockerInstallation)
- [Usage](#usage)
- [Author](#author)

## Docker Installation
Step 1:For Docker installation in VM :
          sudo apt install docker.io
          sudo systemctl enable docker
          sudo systemctl status docker
          sudo systemctl start docker
Step 2: Container creation:
        sudo docker build -t employee_feedback_form .
When we run the above command , output will be in the form of an image.
Step 3: Run the docker image :
        sudo docker run -p 5000:5000 employee_feedback_form
Step 4:
      Open the browser and launch the web application using IP address.

## Usage

1.Provide First name , Last name, email and message  in the form and click on submit button.
2.On click of "Submit", employee will be prompted with a message "Thankyou for providing the feedback."

## Author
- [G23AI2032](https://github.com/G23AI2032/Assignment1_docker)







