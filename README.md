#Calipso

This repository contains a repository-like API for accessing data thru REST 

List of available endpoints:
* HTTP GET  /data/reports/               - returns information about available reports (top 20)
* HTTP GET  /data/reports/{reportId:int} - returns information about reports
* HTTP POST /data/reports/{reportId:int} - updates a report specified and returns the operation result
