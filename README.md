# Credentials generator
The system is developed for exchanging the pair of keys and all necessary information about server and entering ports for WireGuard VPN connection within the faculty network.

### Specifications
Main functionalitites are creation of WG session credentials, based on data stored in Oracle DB. WireGuard is Peer-to-Peer VPN, so it requires PGP encryption for establishing secure connection.
Every student receives pair of keys for server, and have to use previoulsy generated PGP keys.
Aditional functionality provides fully generated configuration file for clients.
Another PLSQL engine creates sessions for student group, with expiration date.
Oracle APEX provide possibility for adapting the User Interface, so changes of environments are possible and easy to do.

### Licence
The authors of this project are student of final year of University of Maribor. 


