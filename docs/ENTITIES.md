# Benötigte Entitäten (Übersicht)

## Helper (Input)
- input_number.evcc_batt_price_limit
- input_number.evcc_batt_capacity_kwh
- input_number.evcc_batt_limit_min_delta_ct
- input_number.evcc_batt_limit_cooldown_min
- input_datetime.evcc_batt_limit_last_set
- input_boolean.evcc_battery_no_discharge
- input_boolean.evcc_battery_automatik (oder input_boolean.evcc_batterie_automatik)

## Preise (Tibber)
- sensor.tibber_price_raw (today/tomorrow Attribute)

## Batterie
- sensor.sn_3017439174_battery_soc_total
- sensor.battery_power_w (falls genutzt)

## PV / Forecast
- sensor.pv_power_total
- sensor.pv_forecast_resttag_heute_gesamt
- sensor.pv_forecast_morgen_gesamt
- binary_sensor.pv_forecast_unplausibel_mittag_2000w

## Hausverbrauch
- sensor.eigenverbrauch

## Monatsziel / Kosten (wenn genutzt)
- sensor.netzbezug_monat_v7
- sensor.kosten_netzbezug_monat_v7
