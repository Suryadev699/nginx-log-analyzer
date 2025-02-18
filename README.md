# nginx-log-analyzer

This project is a simple shell script to analyze Nginx access logs. It provides insights into the most frequent IP addresses, requested paths, response status codes, and user agents.

## Prerequisites

- Bash
- `awk` command

## Usage

1. Place your Nginx access log file in the same directory as the script and name it `nginx-access.log`.
2. Run the script:

    ```sh
    ./nginx_log_analyser.sh
    ```

## Output

The script will output the following information:

- Top 5 IP addresses with the most requests
- Top 5 most requested paths
- Top 5 response status codes
- Top 5 user agents

## Example

```sh
Top 5 IP addresses with the most requests:
  50 192.168.1.1
  30 192.168.1.2
  20 192.168.1.3
  10 192.168.1.4
   5 192.168.1.5

Top 5 most requested paths:
  40 /index.html
  30 /about.html
  20 /contact.html
  10 /products.html
   5 /services.html

Top 5 response status codes:
  50 200
  30 404
  20 500
  10 301
   5 302

Top 5 user agents:
  50 Mozilla/5.0
  30 curl/7.68.0
  20 PostmanRuntime/7.26.8
  10 Wget/1.20.3
   5 Python-urllib/3.8
```
created as part of the project https://roadmap.sh/projects/nginx-log-analyser
