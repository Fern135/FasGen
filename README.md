# FasGen
Fast Api Secure Generator 

FasGen new <project-name> [options]

Options:
  -d, --docker          Include Dockerfile (+ docker-compose if chosen in prompts)
  --psg                 Enable Postgres support (will ask if you want it in compose)
  --msql                Enable MySQL support (will ask if you want it in compose)
  --redis               Enable Redis support (will ask if you want it in compose)
  --ngnx                Provide Nginx reverse-proxy option (will ask include in compose)
  --ci                  Add GitHub Actions CI: lint/test/build
  --port <n>            API port (default: 8000)
  --py <ver>            Python version for Docker (default: 3.13.2)
  -h, --help            Show help
