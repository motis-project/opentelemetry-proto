cmake_minimum_required(VERSION 3.21)
project(opentelemetry-proto)

set(OTELCPP_PROTO_PATH
        "${CMAKE_CURRENT_LIST_DIR}"
        CACHE PATH "Path to opentelemetry-proto")
