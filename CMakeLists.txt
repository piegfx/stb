cmake_minimum_required(VERSION 3.20)
project(stb)

add_library(${PROJECT_NAME}
        stb_c_lexer.h
        stb_connected_components.h
        stb_divide.h
        stb_ds.h
        stb_dxt.h
        stb_easy_font.h
        stb_herringbone_wang_tile.h
        stb_hexwave.h
        stb_image_resize2.h
        stb_image_write.h
        stb_include.h
        stb_leakcheck.h
        stb_perlin.h
        stb_rect_pack.h
        stb_sprintf.h
        stb_textedit.h
        stb_tilemap_editor.h
        stb_truetype.h
        stb_voxel_render.h
        stb_vorbis.c
)

target_include_directories(${PROJECT_NAME} PUBLIC .)