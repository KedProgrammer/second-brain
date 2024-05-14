
## Tittle: Yello 
# date: 2024-03-21
# tags: 
      - yello

##  Commands
- reload ES for client:  bundle exec rake elasticsearch:reload[client] 
curl -XGET "http://localhost:9200/_cat/indices"

curl " http://localhost:9200/microsoft_campaign_search_event/_search?pretty=true" -d '{"query": {"match_all": {}}}'


curl " http://localhost:9200/microsoft_campaign_insert_event/_search?pretty=true" -d '{"query": {"match_all": {}}}'


curl " http://localhost:9200/microsoft_object_candidate/_search?pretty=true" -d '{"query": {"term": {"object_id":"20694"}}}'

## Email candidate templates and external registration event
    when you create a form template from candidate email template view, it is saved in the EmailTemplate table, then if you go to external registration settings  and turn on send automatic flollow-up email, you pick the email template that you just created but the
    system is going to create another EmailTemplate record with the  name custom **custom_email_template**, now the external registration settings is going to reference that new custom form.The new custom form is going to have a reference to its parent

## credentials

TEAMS_CLIENT_ID: 08b25b11-5e02-4b03-ac90-8da57e70453c
TEAMS_CLIENT_SECRET: tBR8Q~b54Ib6dcG4VBeiwP84UORXRUoGAWEU5aYF
