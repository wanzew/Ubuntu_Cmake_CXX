# include_directories(${PROJECT_SOURCE_DIR}/include)

# SET(DIR_PACKAGE_SRCS template.hpp)
AUX_SOURCE_DIRECTORY(. DIR_PACKAGE_SRCS)
ADD_LIBRARY(printFunc ${DIR_PACKAGE_SRCS})