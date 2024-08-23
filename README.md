
# ProxyHunt

![image](https://raw.githubusercontent.com/xReverseLabs/ProxyHunt/main/proxyhunt.png)

## Overview

**ProxyHunt** is a powerful Go-based tool developed by xReverseLabs, designed to scrape proxies from various sources and test their validity against popular websites like Google and Bing, or a custom URL of your choice. The tool offers flexibility in choosing the type of proxies to scrape and allows for real-time checking of proxy availability.

## Features

- **Multi-Type Proxy Scraping**: Supports scraping HTTP, HTTPS, SOCKS5, SOCKS4, and all proxies.
- **Flexible Proxy Checking**: Allows testing proxies against Google, Bing, or a custom URL.
- **Real-Time Results**: Saves the results of live and dead proxies as they are checked.
- **Concurrency**: Leverages goroutines to perform concurrent proxy checking, making the process efficient and fast.
- **Customizable**: Choose your preferred testing URL and manage the number of concurrent checks.

## Usage

1. **Select the type of proxies to scrape**:
   After running the tool, you will be prompted to choose the type of proxies to scrape from the following options:
   - HTTP Proxies
   - HTTPS Proxies
   - SOCKS5 Proxies
   - SOCKS4 Proxies
   - All Proxies

2. **Choose whether to check the proxies**:
   After scraping, you can choose to test the scraped proxies against:
   - `google.com`
   - `bing.com`
   - A custom URL of your choice

3. **View results**:
   - `Results.txt`: Contains all the scraped proxies.
   - `live.txt`: Contains proxies that were successfully tested.
   - `dead.txt`: Contains proxies that failed the test.

## Contributing

We welcome contributions to improve ProxyHunt! Feel free to submit issues or pull requests.
