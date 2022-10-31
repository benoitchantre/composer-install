# Composer install

This composite action simplifies the installation of PHP dependencies with Composer.

## Usage

```yaml
- name: Setup SSH key
  uses: benoitchantre/composer-install@1.0.0
  with:
    # Composer install options.
    # --no-interaction --no-progress are always used.
    # Optional.
    options: '--no-dev --classmap-authoritative'
```

## License

The scripts and documentation in this project are released under the [MIT License](LICENSE).
