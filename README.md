# Usage
First, you **must** configure SSH host aliases in your SSH client configuration. This is most commonly found at ```$HOME/.ssh/config```.

Next, place the ```dsh``` script in your ```$PATH```.

Once ```dsh``` is in your ```$PATH```, run the following:

```
chmod +x /path/to/dsh
```

You should now be able to run commands on remote docker instances!

```
dsh host1 docker compose pull
dsh host2 docker ps
dsh host1 docker compose up -d
```
