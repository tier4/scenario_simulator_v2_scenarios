cmake_minimum_required(VERSION 3.16.3)

project(scenario_simulator_v2_scenarios)

find_package(ament_cmake REQUIRED)

install(
  DIRECTORY
        catalog
        basic
        Ego
        MiscObject
        Pedestrian
        Vehicle
        map
        workflow
  DESTINATION share/${PROJECT_NAME})

ament_package()
