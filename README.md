# MainCard-Proxy_Server
This application proxy server was inherited for hosting several components of a single page application.

## Motivation

This project was developed to gain a fundamental understanding of scalability in service-oriented architecture.

### Prerequisites


### Installing

To install dependencies, run 

  ```
  npm install
  ```

## Deployment

### AWS

To start web service

  1. To establish port forwarding, run
  ```
  sudo iptables -t nat -A PREROUTING -i eth0 -p tcp --dport 80 -j REDIRECT --to-port 3000
  ```

  2. In Similar-Listings-Recommendations directory, run
  ```
  npm run proxy-dev
  ```

## Built with

#### Tech/frameworks used

* React
* NodeJs/Express

#### Features

* AWS EC2 (Optional)

## Authors

Moe Mosaad

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Nick Bisignano
* Paul Lee
* Jonathan Raitses

MIT © Moe Mosaad
