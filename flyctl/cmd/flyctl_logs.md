# _flyctl logs_

View App logs

### About

View application logs as generated by the application running on 
the Fly platform.

Logs can be filtered to a specific instance using the --instance/-i flag or 
to all instances running in a specific region using the --region/-r flag.

### Usage
```
flyctl logs [flags]
```

### Options

```
  -a, --app string        App name to operate on
  -c, --config string     Path to an app config file or directory containing one (default "./fly.toml")
  -h, --help              help for logs
  -i, --instance string   Filter by instance ID
  -r, --region string     Filter by region
```

### Global Options

```
  -t, --access-token string   Fly API Access Token
  -j, --json                  json output
  -v, --verbose               verbose output
```

### See Also

* [flyctl](/docs/flyctl/help/)	 - The Fly CLI
