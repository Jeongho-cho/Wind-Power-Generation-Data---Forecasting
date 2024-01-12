The columns in the data are as follows:

Time - Hour of the day when readings occurred
	판독값이 발생한 시간
temperature_2m - Temperature in degrees Fahrenheit at 2 meters above the surface	
	표면 위 2미터의 온도(화씨)
relativehumidity_2m - Relative humidity (as a percentage) at 2 meters above the surface
	표면 위 2미터의 상대 습도(백분율)
dewpoint_2m - Dew point in degrees Fahrenheit at 2 meters above the surface
	표면 위 2미터에서의 이슬점(화씨)
windspeed_10m - Wind speed in meters per second at 10 meters above the surface
	표면 위 10m에서의 풍속(초당 미터)
windspeed_100m - Wind speed in meters per second at 100 meters above the surface
	표면 위 100m에서의 풍속(초당 미터)
winddirection_10m - Wind direction in degrees (0-360) at 10 meters above the surface (see notes)
	표면 위 10m에서의 풍향(0~360도)
winddirection_100m - Wind direction in degrees (0-360) at 100 meters above the surface (see notes)
	표면 위 100미터에서의 풍향(0~360도)
windgusts_10m - Wind gusts in meters per second at 100 meters above the surface
	표면 위 100미터에서의 돌풍
Power - Turbine output, normalized to be between 0 and 1 (i.e., a percentage of maximum potential output)
	0과 1 사이로 정규화된 터빈 출력(즉, 최대 잠재 출력의 백분율)
Notes:
	1) Likely many of these variables will not be very relevant. They are included here but do not need to be included in the final models.
	2) Degrees are measured from 0 to 360. Since 0 and 360 represent the same spot on a circle, consider transforming these using sine and/or cosine. Also consider converting them to radians, instead of degrees.
	3) Each location can have a different model. There is no reason to build one model to work for all locations.
1) 아마도 이러한 변수 중 상당수는 그다지 관련성이 없을 것입니다. 여기에는 포함되어 있지만 최종 모델에는 포함될 필요는 없습니다.
2) 각도는 0부터 360까지 측정됩니다. 0과 360은 원의 동일한 지점을 나타내므로 사인 및/또는 코사인을 사용하여 변환하는 것을 고려하십시오. 또한 각도 대신 라디안으로 변환하는 것도 고려해 보세요.
3) 각 위치마다 모델이 다를 수 있습니다. 모든 위치에서 작동하는 하나의 모델을 구축할 이유가 없습니다.
