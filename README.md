# go-website-health

# Description
`go-website-health` is a tiny program written in Go that checks if a given domain is up or down. It uses the TCP protocol to determine the reachability of the domain.

# Installation

1. Make sure you have Go installed on your machine. You can download it from [here](https://golang.org/dl/).
2. Clone this repository:
    ```sh
    git clone <repository-url>
    ```
3. Navigate to the project directory:
    ```sh
    cd go-website-health
    ```
4. Install the dependencies:
    ```sh
    go get github.com/urfave/cli/v2
    ```

 

# Usage

Run the following command to check if a domain is up or down:
```sh
`./website-health-checker --domain <domain-name> `

# Flags
`--domain, -d`: Domain name to check. (Required)
`--port, -p`: Port number to check. (Optional, defaults to 80)
Examples
To check if `google.com` is up or down on the default port (80):

`./website-health-checker --domain google.com`



