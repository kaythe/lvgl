target_sources(LVGL-Test PRIVATE    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_hal/lv_hal_disp.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_hal/lv_hal_indev.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_hal/lv_hal_tick.c)