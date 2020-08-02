# `rest.base` - ContEco

ContEco REST base image for InfoMetis REST API client implementations, providing the base functionality using curl.  
See `conteco.docs.overview` for more information on the ContEco ecosystem.

This image is the base for API implementations based on bash scripts.

# Configuration

This base image implements the execution of a request using curl.

It implements a global flag for logging: CONTECO_STATIC_REST_BASE_API_LOGGING.  
This flag can have 3 values - as a space delimited list - REQUEST RESPONSE TRACE.

REQUEST  
Log the request as received by execute-curl.

RESPONSE  
Log the reponse as returned by execute-curl.

TRACE  
Log the output of --trace-ascii of the curl request.
