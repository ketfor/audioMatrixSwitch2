idf_component_register(SRCS "src/time_sync.c"
                    INCLUDE_DIRS "include"
                    PRIV_REQUIRES nvs_flash esp_event esp_netif esp_timer)
