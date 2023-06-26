# Utiliza la imagen base de .NET 7 SDK
FROM mcr.microsoft.com/dotnet/sdk:7.0

RUN apt-get update \
    && apt-get install -y --no-install-recommends \
        apt-transport-https \
        curl \
        ca-certificates \
        gnupg \
        lsb-release \
        git

# Define el directorio de trabajo
WORKDIR /workspace

# Expone el puerto 5000 para aplicaciones web en .NET
EXPOSE 5000