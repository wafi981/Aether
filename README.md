# Aether
Aether project Helm charts

# Step 1: 
Set ```name``` and ```repo``` variable, where name is the custom name of charts and repo is the link.

```
export name="Aether"
export repo="https://charts.aetherproject.org"
```

# Step 2:
Run gen_array script to generate your array.

```
chmod 777 gen_array.sh
./gen_array
```

# Step 3:
Make a docs folder and run the start.sh script which uses the array to pull your charts.

```
mkdir docs
chmod 777 start.sh
./start.sh
```

# Step 4:
Once the charts are inside the docs folder, run this command from root dir

```
helm repo index .

```


