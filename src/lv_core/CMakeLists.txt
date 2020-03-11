target_sources(LVGL-Test PRIVATE    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_core/lv_group.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_core/lv_indev.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_core/lv_disp.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_core/lv_obj.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_core/lv_refr.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_core/lv_style.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_core/lv_debug.c)