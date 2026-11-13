idf_component_register(SRCS "app_main.c" "cooling_system.c" "flow_calc.c" "flow_sensor.c" "can_tx.c" "ads1115.c" "temp_calc.c"
                    INCLUDE_DIRS "."
                    REQUIRES esp_driver_gpio
                             esp_driver_i2c
                             esp_driver_pcnt
                             esp_driver_twai
                             esp_timer
                             sdm-utils)
