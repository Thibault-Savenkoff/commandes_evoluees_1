# Commandes évoluées I

## Q1

```bash
cat > telephone << 'EOF'
arthur 8316
toto 8321
titi 8623
zoe 8520
alfred 8317
john 8521
arthur 8316
EOF
```

a) `cat telephone`

b) `cat telephone | sort`

c) `cat telephone | sort -ru`

d) `grep 83 telephone`

e) `grep 83 telephone | sort -ru`

f) `grep 83 telephone | sort -u | sort -k2,2nr`

g) `sort -u telephone | wc -l`

h) `grep 83 telephone | sort -u | wc -l`

i) `head -n 6 telephone | tail -n 3`

## Q2

a) `grep a words`

b) `grep ^t words`

c) `grep ^ex.+se$ words`