Axios api

1. Axios GET api takes two arguments url and options which is a object with headers and params.

Why apis are calling 2 times

That is because of react strict mode, It will check the data twice, is there any change or not, if there is a change it will throw an error.