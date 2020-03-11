target_sources(LVGL-Test PRIVATE    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_draw/lv_draw.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_draw/lv_draw_arc.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_draw/lv_draw_basic.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_draw/lv_draw_img.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_draw/lv_draw_label.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_draw/lv_draw_line.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_draw/lv_draw_rect.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_draw/lv_draw_triangle.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_draw/lv_img_cache.c
                                    ${CMAKE_SOURCE_DIR}/lvgl/src/lv_draw/lv_img_decoder.c)