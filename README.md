# go-s3-uploader

## Usage
I made this to backup the many hours of cat videos on my external hard drive. Worth the S3 storage costs.

Run the script from the command line using positional arguments for local filesystem path, S3 bucket name, S3 path prefix.
`go run main.go <replace-with-local-path> <replace-with-bucket-name> <replace-with-s3-path-prefix>`

- Excludes macOS filenames that start with `._`

I used examples from this documentation and modified them for my needs:
* [AWS SDK for Go](https://aws.github.io/aws-sdk-go-v2/docs/sdk-utilities/s3/)
* Go [path/filepath](https://pkg.go.dev/path/filepath) package.