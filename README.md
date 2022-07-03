# workflows

Reusable workflows for my repositories

## hadolint

```yaml
jobs:
  uses: Roang-zero1/workflows/.github/workflows/hadolint.yml@v1
```

## sh-checker

```yaml
jobs:
  uses: Roang-zero1/workflows/.github/workflows/sh-checker.yml@v1
```

### Inputs

#### `shfmt_args`

`shfmt` arguments to be passed along.  
Defaults to `-i 2 -ci` (2 space indent, indented switch cases).

## create-release

```yaml
jobs:
  uses: Roang-zero1/workflows/.github/workflows/create-release.yml@v1
```

### Inputs

#### `update_existing`

Allow updating of existing releases.
Defaults to `true`.

## update-major-version-tag

```yaml
jobs:
  update-major-version-tag:
    uses: Roang-zero1/workflows/.github/workflows/create-release.yml@v1
```

### Inputs

#### `force_push_tag`

Allow updating of existing releases.
Defaults to `true`.
