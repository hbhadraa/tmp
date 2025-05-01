Key | Purpose
action | "create" / "update" / "delete"
workflowId | Logical identifier for the transfer function
lambda | Lambda-specific config (runtime, env, memory, etc.)
source | Only for "create" – defines S3 event trigger setup
target | Optional target-specific metadata
iamRole | Role and policies needed for Lambda
functionName | Used for "update" or "delete" to identify existing Lambda
