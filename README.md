# nikto-scan docker action

Scan an endpoint using the Nikto open source scanner

## Inputs

## `host`

**Required** The host that shall be scanned

## Outputs

## `results`

The JSON formatted scan results


## Example usage

uses: glennadjrussell/nikto-scan@v1
with:
  host: X.X.X.X:3000

