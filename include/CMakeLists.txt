# Install the opencv.hpp header file to the specified include path under the opencv2 directory
install(
    FILES "opencv2/opencv.hpp"
    DESTINATION ${OPENCV_INCLUDE_INSTALL_PATH}/opencv2
    COMPONENT dev
)
