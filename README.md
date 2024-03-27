# Composer install

This composite action simplifies the installation of PHP dependencies with Composer.

## Usage

```yaml
- name: Composer install
  uses: benoitchantre/composer-install@1.0.1
  with:
    # Composer install options.
    # --no-interaction --no-progress --ansi are always used.
    # Optional.
    options: '--no-dev --classmap-authoritative'
```

## License

The scripts and documentation in this project are released under the [MIT License](LICENSE).
