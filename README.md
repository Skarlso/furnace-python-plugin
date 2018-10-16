Install tools:

`python3 -m pip install --user grpcio-tools`
`python3 -m pip install --user grpcio_health_checking`

Generating the Code:

`python3 -m grpc_tools.protoc -I ./ --python_out=. --grpc_python_out=. ./furnace.proto`
