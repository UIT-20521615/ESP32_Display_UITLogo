set(component_srcs "ssd1306.h" "ssd1306.c" "ssd1306_fonts.h" "ssd1306_fonts.c")

idf_component_register(SRCS "ssd1306.c" "ssd1306_fonts.c" "${component_srcs}"
                       PRIV_REQUIRES driver
                       INCLUDE_DIRS ".")