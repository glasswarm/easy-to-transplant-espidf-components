idf_component_register(SRCS "Wifi_AP_init.c"
                    	INCLUDE_DIRS "."
			                         "./Wifi_AP_init"
					    PRIV_REQUIRES esp_wifi
								      nvs_flash
		    )
