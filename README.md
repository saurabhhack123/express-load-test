Simple load test

1. clone the repository
2. npm install

Reference API

URL: http://localhost:3030/loadtest
METHOD: POST
REQUEST: 
{
	"url":"http://18.207.54.190:9000/userChat",             ---> your api url
	"method":"POST",                                        ---> http method
	"request": {                                            ---> request
        "mes": "book a flight from bangalore to mumbai",
        "stack": [],
        "gmt_offset": "+5:30"
    },
    "count": 20                                             ---> loop execute count
}