target_sources(LVGL-Test PRIVATE    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_font/lv_font.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_font/lv_font_fmt_txt.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_font/lv_font_roboto_12.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_font/lv_font_roboto_12_subpx.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_font/lv_font_roboto_16.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_font/lv_font_roboto_22.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_font/lv_font_roboto_28.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_font/lv_font_roboto_28_compressed.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_font/lv_font_unscii_8.c)