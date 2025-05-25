idf_component_register(SRCS "wifi_scan.cc"
                    INCLUDE_DIRS "."
					PRIV_REQUIRES esp_wifi nvs_flash)
