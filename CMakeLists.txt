set(req driver freertos esp_timer esp_rom)
idf_component_register(SRCS "HX711_ADC.cpp"
                    INCLUDE_DIRS "include"
                    REQUIRES ${req})
