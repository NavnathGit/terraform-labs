
```sh
module "demomodule" {
  source = "git::https://github.com/zealvora/tmp-repo.git"
}
```

### Example 2: Generic GIT Repository with Specific branch:
```sh
module "demomodule" {
  source = "git::https://github.com/zealvora/tmp-repo.git?ref=development"
}
```

### Example 3: GitHub Source:
```sh
module "demomodule" {
  source = "github.com/zealvora/tmp-repo"
}
```

### Initialization Command:
```sh
terraform init
```
