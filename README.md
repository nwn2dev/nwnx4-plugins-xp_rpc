protoc --go_out=./nwnx4.org/proto --go-grpc_out=./nwnx4.org/proto --go_opt=paths=source_relative --go-grpc_opt=paths=source_relative -Iproto $(find proto -iname "*.proto")