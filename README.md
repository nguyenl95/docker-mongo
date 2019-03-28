## my mongo service
    with ability to use --bind_ip_all option, which official version doesn't allow

### todo:
- mount volumes in proper folder

- integrate with my own CI/CD

- a way to backup/recover existing data (in script format)

### faq:
- to build mongo image

    docker-compose up --build mongo
    
- what's next?

    build -> tag -> push to local registry server