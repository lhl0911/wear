//获取城市天气
String url = "http://t.weather.itboy.net/api/weather/city/101160401";
		Map<String, String> result3 = HttpClientUtil.get(url, null, null);
		String result=result3.get("result");
		JSONObject ob=JSON.parseObject(result);
		JSONObject ob2=ob.getJSONObject("data");
		String shidu=(String) ob2.get("shidu");
		String quality=(String) ob2.get("quality");
		String wendu=(String) ob2.get("wendu");
		JSONArray forecast=ob2.getJSONArray("forecast");
		JSONObject yesterday = (JSONObject) forecast.get(0);	
			String ymd=(String) yesterday.get("ymd");
			String week=(String) yesterday.get("week");
			String fl=(String) yesterday.get("fl");
			String type=(String) yesterday.get("type");
			String fx=(String) yesterday.get("fx");
