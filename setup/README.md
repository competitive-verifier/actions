# Set up competitive-verifier
A composite action that set up competitive-verifier command.

See [action.yml](action.yml) or [competitive-verifier/competitive-verifier](https://github.com/competitive-verifier/competitive-verifier).

## Example

```yml
      - name: Set up competitive-verifier
        uses: competitive-verifier/actions/setup@v2
        with:
          cache-pip: true
```