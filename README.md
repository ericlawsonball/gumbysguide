# **Gumby's Guide Website**

## todo
1. Format according to python standards
2. Move handlers to folder
3. Add login screen
7. Check cookie_secret
8. Read/write to database

## References
1. https://cdnjs.com/libraries/jquery
2. https://cdnjs.com/libraries/semantic-ui
3. https://semantic-ui.com/

## Common commands
- git add . && git commit -m "fixed things" && git push heroku master
- heroku local web
- http://localhost:5000
- heroku pg:psql
- ALTER TABLE mytable ADD COLUMN mycolumn variable_name var_type
- \q quits psql
- \d mpg lists types
- cd ~/sand*/gum* && heroku pg:psql
- heroku config
- heroku config set:VAR_TO_CHANGE='value to set'
- heroku config:get CONFIG-VAR-NAME -s  >> .env
 (Saves config variables to local environment)
- http://stackoverflow.com/questions/12505158/generating-a-uuid-in-postgres-for-insert-statement
- uuid_generate_v4()
