set(srcs "main.c"
        "board.c"
        "DHT.c"
        )

idf_component_register(SRCS "${srcs}"
                    INCLUDE_DIRS  ".")
