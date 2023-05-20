# PRO-C180-Student-Boilerplate

https://api.mapbox.com/directions/v5/mapbox/driving/${coordinates.source_lon}%2C${coordinates.source_lat}%3B${coordinates.destination_lon}%2C${coordinates.destination_lat}?alternatives=true&geometries=polyline&steps=true&access_token=pk.eyJ1IjoiYXBvb3J2ZWxvdXMiLCJhIjoiY2ttZnlyMDgzMzlwNTJ4a240cmEzcG0xNyJ9.-nSyL0Gy2nifDibXJg4fTA

$.ajax({
    uri:'',
    type:'',
    success:'',
    error:''
})

Note 1: The latitude and longitude are
separated by the comma in the URL.
Note 2: The source and destination are
separated by a semicolon in the URL.
Note 3: The %2C in the URL
represents the comma and %3B
represents the semi-colon. This special
encoding is done for the URLs to
transfer data. %7b--->  {   and %7D--->}

# sample URL 
https://obj.whitehatjr.com/45e69d29-2135-49df-89b7-c7d49f43a022.pdf

# output
https://drive.google.com/file/d/1fMCFEpnMc8zTaEEY5MlIJXNkvb-6Fn8l/view

Didn't complete the else statement