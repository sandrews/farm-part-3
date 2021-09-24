# farm-part-3
Build a FARM stack. Part 3. React is included in this stack.

For a breakdown of the code you can read the associated CodeX article at https://medium.com/codex/creating-a-farm-stack-dev-environment-with-docker-compose-part-3-of-3-react-123bfa8f187a.

# Security
You must add the environment variables MONGO_USER and MONGO_PASSWORD to your environment. You can also add a ".env" file to the root of your system with the environment variables.

Example .env contents

MONGO_USER=root

MONGO_PASSWORD=OTNmYTdjYmZkMjE5ZmYzODg0MDZiYWJh

# Run
You can run the FARM stack by running the following command.

docker-compose up
