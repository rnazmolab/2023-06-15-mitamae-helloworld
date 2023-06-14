# 2023-06-15-mitamae-helloworld

## Notes

### Install mitamae

[itamae-kitchen/mitamae: mitamae is a fast, simple, and single-binary configuration management tool with a DSL like Chef](https://github.com/itamae-kitchen/mitamae/tree/3a053980d5b7c9306f41ef1a8988c3c2acb59420#installation)

```bash
curl -L https://github.com/itamae-kitchen/mitamae/releases/latest/download/mitamae-x86_64-linux.tar.gz \
  | tar xvz
./mitamae-x86_64-linux help
```

```bash
mv mitamae-x86_64-linux mitamae
```

### Run mitamae

[itamae-kitchen/mitamae: mitamae is a fast, simple, and single-binary configuration management tool with a DSL like Chef](https://github.com/itamae-kitchen/mitamae/tree/3a053980d5b7c9306f41ef1a8988c3c2acb59420#getting-started)

```bash
./mitamae local ./recipe.rb
 INFO : Starting mitamae...
 INFO : Recipe: /home/user/recipe.rb
 INFO :   package[nginx] installed will change from 'false' to 'true'
 INFO :   service[nginx] enabled will change from 'false' to 'true'
 INFO :   service[nginx] running will change from 'false' to 'true'
```
