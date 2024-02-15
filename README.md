# Generate PB files
-- use this command to generate pb.go files for protoc file in windows 
protoc --go_out=. --go-grpc_out=. chat.proto


-- go mod tidy