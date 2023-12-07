idf_component_register(SRCS "Wifi_AP.c"
                    	INCLUDE_DIRS "."
			                         "./Wifi_AP"
					    PRIV_REQUIRES esp_wifi
								      nvs_flash
		    )
