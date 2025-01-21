```mermaid
graph TD
    A[HQ-DNS@10.19.110.15] -->|_ldap._tcp.pdc._msdcs.dzsi.net| B[199.7.83.42]
    A -->|_ldap._tcp.pdc._msdcs.dzsi.net| C[192.112.36.4]
    A -->|_ldap._tcp.pdc._msdcs.dzsi.net| D[170.247.170.2]
    E[HQ-AD-Dns@10.22.110.11] -->|_ldap._tcp.pdc._msdcs.dzsi.net| F[192.36.148.17]
    E -->|_ldap._tcp.pdc._msdcs.dzsi.net| G[202.12.27.33]
    E -->|_ldap._tcp.pdc._msdcs.dzsi.net| H[193.0.14.129]
    A -->|_ldap._tcp.pdc._msdcs.dzsi.net| I[192.5.5.241]
    A -->|_ldap._tcp.pdc._msdcs.dzsi.net| J[198.41.0.4]
    A -->|_ldap._tcp.pdc._msdcs.dzsi.net| K[198.97.190.53]
    E -->|_ldap._tcp.pdc._msdcs.dzsi.net| J
    E -->|_ldap._tcp.pdc._msdcs.dzsi.net| K
    A -->|_ldap._tcp.pdc._msdcs.dzsi.net| G
    E -->|_ldap._tcp.pdc._msdcs.dzsi.net| L[192.58.128.30]
    A -->|_ldap._tcp.pdc._msdcs.dzsi.net| L
    M[HQ-AD-Dns@10.22.110.12] -->|_ldap._tcp.pdc._msdcs.dzsi.net| I
    M -->|_ldap._tcp.pdc._msdcs.dzsi.net| F
    M -->|_ldap._tcp.pdc._msdcs.dzsi.net| J
    M -->|_ldap._tcp.pdc._msdcs.dzsi.net| N[192.33.4.12]
    M -->|_ldap._tcp.pdc._msdcs.dzsi.net| H
    M -->|_ldap._tcp.pdc._msdcs.dzsi.net| B
    M -->|_ldap._tcp.pdc._msdcs.dzsi.net| L
    E -->|_ldap._tcp.USOAKL._sites.dc._msdcs.dzsi.net| J
    E -->|_ldap._tcp.USOAKL._sites.dc._msdcs.dzsi.net| G
    E -->|_ldap._tcp.USOAKL._sites.dc._msdcs.dzsi.net| F
    E -->|_ldap._tcp.USOAKL._sites.dc._msdcs.dzsi.net| H
    M -->|_ldap._tcp.USOAKL._sites.dc._msdcs.dzsi.net| B
    M -->|_ldap._tcp.USOAKL._sites.dc._msdcs.dzsi.net| I
    M -->|_ldap._tcp.USOAKL._sites.dc._msdcs.dzsi.net| N
    A -->|_ldap._tcp.USOAKL._sites.dc._msdcs.dzsi.net| G
    M -->|_ldap._tcp.USOAKL._sites.dc._msdcs.dzsi.net| H
    A -->|_ldap._tcp.USOAKL._sites.dc._msdcs.dzsi.net| C
    A -->|_ldap._tcp.USOAKL._sites.dc._msdcs.dzsi.net| D
    A -->|_ldap._tcp.USOAKL._sites.dc._msdcs.dzsi.net| B
    E -->|_ldap._tcp.USOAKL._sites.dc._msdcs.dzsi.net| K
    A -->|_ldap._tcp.USOAKL._sites.dc._msdcs.dzsi.net| J
    ```
