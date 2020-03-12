# Advanced Lane Finding on the Road



The goals / steps of this project are the following:

- Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.
- Apply a distortion correction to raw images.
- Use color transforms, gradients, etc., to create a thresholded binary image.
- Apply a perspective transform to rectify binary image ("birds-eye view").
- Detect lane pixels and fit to find the lane boundary.
- Determine the curvature of the lane and vehicle position with respect to center.
- Warp the detected lane boundaries back onto the original image.
- Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position.





<hr>

## How to run 

- To run this code it is recommended a docker container that has all dependences 
    - pull the container from Docker Hub:   `docker pull udacity/carnd-term1-starter-kit`
    - Then run the container at the container at the directory where this repository is loacated: `docker run -it --rm --entrypoint "/run.sh" -p 8888:8888 -v ${pwd}:/src udacity/carnd-term1-starter-kit` 
    - Then you can run the Jupyter Notebook in this repository