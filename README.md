`environments/dev.bru`:

```bru
vars {
  access_token: <access token generated for site>
  baseURL: https://sandbox.zenodo.org // change as necessary
}
```

[Bruno does not have workflows yet](https://github.com/usebruno/bruno/issues/87), so you will need to run 3 of the scripts (Create minimal/full, Add file, Publish) to create a record on sandbox. This is an example of what the full record looks like using all fields from the documentation https://sandbox.zenodo.org/records/48658

If you are developing locally, you should open the settings and disable SSL/TLS Certificate Verification
