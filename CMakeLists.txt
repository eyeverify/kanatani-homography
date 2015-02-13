project(KANATANI_HOMOGRAPHY)

set(KANATANI_HOMOGRAPHY_SRCS
    Matrix/alg_eigen.cpp
    Matrix/alg_lu.cpp
    Matrix/alg_matutil.cpp
    Matrix/alg_matutil.h
    Matrix/matrix.h
    Matrix/matrix_base.cpp
    Matrix/matrix_base.h
    Matrix/tensor3333.cpp
    Matrix/tensor3333.h
    Matrix/util_gen.cpp
    Matrix/util_gen.h
    Matrix/util_io.cpp
    Matrix/util_io.h
    Matrix/util_kk.cpp
    Matrix/util_kk.h
    Matrix/util_num.cpp
    Matrix/util_num.h
    homoest.cpp
    homoest.h
    mhomoest.cpp)

add_library(kanatani-homography STATIC ${KANATANI_HOMOGRAPHY_SRCS})
