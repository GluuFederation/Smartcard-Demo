## README CAC/PIV card/Certificate Login

Following are the configuration properties for the *cert.py* and *external_cert.py* script:

- **credentials_file**: mandatory property pointing to credentials file in [json] format.
- **crl_max_response_size**: specifies the maximum allowed size of [CRL][crl] response.
- **map_user_cert**: specifies if the script should map new user to local account.
- **use_crl_validator**: enable/disable specific certificate validation.
- **use_generic_validator**: enable/disable specific certificate validation
- **use_ocsp_validator**: enable/disable specific certificate validation.
- **use_path_validator**: enable/disable specific certificate validation.
- **chain_cert_file_path**: mandatory property pointing to certificate chains in [pem] format.

Please refer to the instructions document for the configuration details.