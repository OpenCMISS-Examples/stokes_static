add_executable(stokes_static_fortran stokes_static.F90)

target_link_libraries(stokes_static_fortran PRIVATE OpenCMISS::libOpenCMISS_Fortran)

install(TARGETS stokes_static_fortran DESTINATION bin)
