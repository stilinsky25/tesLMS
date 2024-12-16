name: Example Workflow

on:
  push:
    branches:
      - main

jobs:
  example-job:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout repository content
        uses: actions/checkout@v3

      - name: Print working directory
        run: pwd
