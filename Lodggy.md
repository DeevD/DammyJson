# Lodggy

Lodggy request and response API documentation.



Base URL

```
http://www.lodggy.com
```



## Search

```
POST	/search
```

### Header

```

```

### Parameter

```
search_key		String		require
```

```
page			int			require
```
### Response

```js
{
    "search_in": "Yangon, Myanmar",
    "search_properties": "515 properties",
    "data": [
        {
            "h_id": "id123",
            "h_name": "Amazing Bagan Resort",
            "h_preview_image": "http://lodggy.com/blablabla.jpg",
            "h_five_star": "4",
            "h_location": "Bagan, Nyaung Oo",
            "h_location_latitude": "19.1234124",
            "h_location_longitude": "19.1234124",
            "h_discount": "-30% Today",
            "h_price_before": "$80",
            "h_price_after": "$60",
            "h_per_unit": "per night"
        },
        {
            "h_id": "id123",
            "h_name": "Amazing Bagan Resort",
            "h_preview_image": "http://lodggy.com/blablabla.jpg",
            "h_five_star": "4",
            "h_location": "Bagan, Nyaung Oo",
            "h_location_latitude": "19.1234124",
            "h_location_longitude": "19.1234124",
            "h_discount": "-30% Today",
            "h_price_before": "$80",
            "h_price_after": "$60",
            "h_per_unit": "per night"
        }
    ],
    "current_page": 1,
    "from": 1,
    "last_page": 264,
    "first_page_url": "http://lodggy.com/api/search?page=1",
    "last_page_url": "http://lodggy.com/api/search?page=264",
    "next_page_url": "http://lodggy.com/api/search?page=2",
    "path": "http://lodggy.com/api/search",
    "per_page": 15,
    "prev_page_url": null,
    "to": 15,
    "total": 3958
}
```




