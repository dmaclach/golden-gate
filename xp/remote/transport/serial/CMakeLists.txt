# Copyright 2017-2020 Fitbit, Inc
# SPDX-License-Identifier: Apache-2.0

target_sources(gg-remote
    PRIVATE
        "${CMAKE_CURRENT_LIST_DIR}/gg_remote_parser.c"
        "${CMAKE_CURRENT_LIST_DIR}/gg_remote_serial.c"
        "${CMAKE_CURRENT_LIST_DIR}/gg_remote_serial_io.c"
        "${CMAKE_CURRENT_LIST_DIR}/gg_remote_parser.h"
        "${CMAKE_CURRENT_LIST_DIR}/gg_remote_serial_io.h"
        "${CMAKE_CURRENT_LIST_DIR}/gg_remote_serial.h"
)
