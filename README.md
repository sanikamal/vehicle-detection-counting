# Vehicle Detection and Counting

This project uses `Flask` and `OpenCV` with Haar Cascades to detect and count vehicles in video streams and images.

#### Steps to create Vehicle Detection and Counting
- Loading the image from Internet/Disk
- Resizing and convering the image
- Load the Haar Cascade xml file
- Use Haar Cascade to detect the vehicle in the image/frame
- Use the countour to create a rectangle around the detected vehicle.
- Use Car detection Haar Cascade for Car Detection
- Perform above steps for video
- Save the video/image with Car Detection

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

You will need to have the following software and libraries installed on your system:

- [Python 3.6 or later](https://www.python.org/downloads/)
- [pipenv](https://pypi.org/project/pipenv/)

You can install pipenv using `pip`:

`pip install pipenv`


### Installing

1. Clone the repository:

`git clone https://github.com/your-username/vehicle-detection-counting.git`

2. Navigate to the project directory:

`cd vehicle-detection-counting`

3. Install the dependencies:

`pipenv install`

4. Run the app:

`pipenv run python app.py`

The app will now be running at http://localhost:5000. You can use a web browser to view the output of the vehicle detection and counting.

## Deployment

To deploy this app on a live system, you will need to set up a web server and install the required dependencies. You can use a tool like [Gunicorn](https://gunicorn.org/) to run the app behind a web server such as [NGINX](https://www.nginx.com/).

## Built With

* [Python](https://www.python.org/) - The programming language used
* [OpenCV](https://opencv.org/) - The computer vision library used for vehicle detection
* [Flask](https://flask.palletsprojects.com/) - The web framework used to create the app
* [pipenv](https://pipenv.pypa.io/en/latest/) - The dependency management tool used

## Contributing

If you would like to contribute to this project, please read the [CONTRIBUTING.md](CONTRIBUTING.md) file for details on the code of conduct and the process for submitting pull requests.


## Authors

* **Sani Kamal** - *Initial work* - [sanikamal](https://github.com/sanikamal)

See also the list of [contributors](https://github.com/sanikamal/vehicle-detection-counting/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.

## Acknowledgments

* Hat tip to the developers of OpenCV and Flask for creating such powerful tools
* Inspiration for this project came from a need to improve traffic management in urban areas

