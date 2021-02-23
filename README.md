## Rockpi4 StandardNotes Server/Web Install

After cloning this repository~~

```bash
cd rp4standardnotes
# Make changes to any of the configuration files at your leasure..

# .. Then
git clone https://github.com/standardnotes/syncing-server.git
git clone https://github.com/standardnotes/web.git

# docker-compose up
docker-compose -f docker-compose.yml -f docker-compose.raspberry-pi.yml up -d
```

By default you should be able to access the server at http://localhost:3001
