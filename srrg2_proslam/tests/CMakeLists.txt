catkin_add_gtest(test_feature_extractors test_feature_extractors.cpp)
target_link_libraries(test_feature_extractors
  srrg2_proslam_tracking_library
)

catkin_add_gtest(test_correspondence_finders test_correspondence_finders.cpp)
target_link_libraries(test_correspondence_finders
  srrg2_proslam_tracking_library
)

catkin_add_gtest(test_measurement_adaptors test_measurement_adaptors.cpp)
target_link_libraries(test_measurement_adaptors
  srrg2_proslam_tracking_library
)

catkin_add_gtest(test_scene_clippers test_scene_clippers.cpp)
target_link_libraries(test_scene_clippers
  srrg2_proslam_tracking_library
)

catkin_add_gtest(test_aligners test_aligners.cpp)
target_link_libraries(test_aligners
  srrg2_proslam_tracking_library
)

catkin_add_gtest(test_projective_point_ekf test_projective_point_ekf.cpp)
target_link_libraries(test_projective_point_ekf
  srrg2_proslam_tracking_library
)

catkin_add_gtest(test_projective_depth_point_ekf test_projective_depth_point_ekf.cpp)
target_link_libraries(test_projective_depth_point_ekf
  srrg2_proslam_tracking_library
)

catkin_add_gtest(test_stereo_projective_point_ekf test_stereo_projective_point_ekf.cpp)
target_link_libraries(test_stereo_projective_point_ekf
  srrg2_proslam_tracking_library
)

catkin_add_gtest(test_mergers test_mergers.cpp)
target_link_libraries(test_mergers
  srrg2_proslam_tracking_library
)

catkin_add_gtest(test_trackers test_trackers.cpp)
target_link_libraries(test_trackers
  srrg2_proslam_tracking_library
)

catkin_add_gtest(test_landmark_estimators test_landmark_estimators.cpp)
target_link_libraries(test_landmark_estimators
  srrg2_proslam_tracking_library
)

catkin_add_gtest(test_place_recognition test_place_recognition.cpp)
target_link_libraries(test_place_recognition
  srrg2_proslam_tracking_library
)

catkin_add_gtest(test_loop_closing test_loop_closing.cpp)
target_link_libraries(test_loop_closing
  srrg2_proslam_tracking_library
)
