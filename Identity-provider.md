# Identity Provider
An identity provider is a tool used to enable login and access to all the systems within the platform. It can alse be used as authorization tool to manage access to relevant tool/data accross the system.

In a multi-platform environment, an strong identity provider is required to manage users accross systems. 

Below is the comparision between few identified tools.

| | [Aerobase](https://aerobase.io/iam) | [Keycloak](https://www.keycloak.org/) | [WSO2 Identity Server](https://wso2.com/identity-and-access-management) | [Gluu](https://www.gluu.org/) | [CAS](https://apereo.github.io/cas/) | [OpenAM](https://github.com/OpenIdentityPlatform/OpenAM/) | [Shibboleth IdP](https://www.shibboleth.net/products/identity-provider/) |
| --- | --- | --- | --- | --- | --- | --- | --- |
| OpenID Connect/OAuth support | yes | yes | yes | yes | yes | yes | **third-party** |
| Multi-factor authentication | yes | yes | yes | yes | yes | yes | yes |
| Admin UI | yes | yes | yes | yes | yes | yes | **no** |
| OpenJDK support | yes | yes | [yes](https://docs.wso2.com/display/IS560/Installation+Prerequisites) |  |  | [yes](https://backstage.forgerock.com/knowledge/kb/book/b16240196#openjdk) | **no** |
| Identity brokering | yes | yes | yes |  |  |  |  |
| Middleware | NGINX, Wildfly | Wildfly, JBOSS | **WSO2 Carbon** | Jetty, Apache HTTPD | any Java app server | any Java app server | Jetty, Tomcat |
| Open source | yes | yes | **Note 1** | yes | yes | yes | yes |
| Commercial support | yes | no | yes | yes | **third-party** | yes | **third-party** |
| Add federation metadata | **no**  | **no** |  |  |  |  | yes |
| Add metadata from URL | **no** | **no** |  |  |  |  | yes |
| Installation | trivial |easy |  |  |  |  | **difficult** |


1. The downloadable binaries on their site don't appear to include the latest security patches. While you could compile and package yourself from the source code, it's not clear if the latest security patches are open-sourced. (http://lists.jboss.org/pipermail/keycloak-user/2016-August/007281.html)

reference: https://gist.github.com/yanivmn/16e5fdf75d2de28650b00a150209d734

## Conclusion
Based on the above comparision, keycloak is the tool of choice for the current system.
