# SAM Cheatsheet

sam --version                          # Shows the installed SAM CLI version.
sam validate                           # Checks that your template.yaml syntax and resources are valid.
sam build                              # Packages your Lambda source code and dependencies into .aws-sam/build/ for deployment.
sam deploy --guided                    # Deploys your SAM stack to AWS interactively (asks for stack name, region, permissions, etc.).
sam sync --stack-name <name> --watch   # (Optional) Automatically syncs code changes to AWS during development.
sam local invoke                       # Runs a Lambda function locally using Docker (optional if Docker is installed).
