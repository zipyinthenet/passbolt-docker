# passbolt-docker

Fichero docker-compose para levantar passbolt en contenedores , y a parte un contenedor mysql para su funcionamiento

Poner atención a las variables (enviorenment) de mail server
      #SMTP MAIL SRV
      #EMAIL_DEFAULT_FROM_NAME: "Passbolt"  # From email username
      EMAIL_DEFAULT_FROM_NAME: "passbolt"  # From email username
      #EMAIL_DEFAULT_FROM: "you@localhost"  # From email address
      EMAIL_DEFAULT_FROM: "passbolt@example.com"  # From email address
      EMAIL_TRANSPORT_DEFAULT_HOST: "mail.example.com"  # Server mail hostname
      EMAIL_TRANSPORT_DEFAULT_PORT: "25"  # Server port
      #EMAIL_TRANSPORT_DEFAULT_USERNAME: "null"  # Username for email server auth
      EMAIL_TRANSPORT_DEFAULT_USERNAME: "passbolt"  # Username for email server auth
      #EMAIL_TRANSPORT_DEFAULT_PASSWORD: "null"  # Password for email server auth
      EMAIL_TRANSPORT_DEFAULT_PASSWORD: "alumno"  # Password for email server auth
      #EMAIL_TRANSPORT_DEFAULT_TLS: "null"  # Set tls