# Nginx proxy

Ansible recipe to configure a nginx as proxy server.

## Role Variables

Option | Description
---|---
`nginx_enabled` | Enable nginx service on boot.
`nginx_state` | State of nginx service.
`app_config` | The path to application config.
`app_name` | The name of the application, uses to create application configuration, e.g.  should be a shorthand, lowercase and not contain any whitespaces.
`app_ip` | The internal ip address of the web application.
`app_port` | The port used by application.
`app_fqdn` | Fully qualified domain name of the application. Non-www version.

## License

Licensed under the [MIT license](http://mit-license.org/vitalk).

## Self-Promotion

Created by Vital Kudzelka.

Open [a GitHub issue](https://github.com/vitalk/ansible-nginx-proxy) if you have any suggestions or found a bug.
