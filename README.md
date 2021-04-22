# Interesting diffs

Changes item properties and armor class:

```
terraform plan -var battle_ready=false
```

Changes level and proficiency bonus, no nested blocks change:

```
terraform plan -var party_xp=1000
```

Full resource diff:

```
terraform plan -var kobold_count=7
```
