### mattermost-app-productboard
Mattermost ProductBoard App (integration)

### Connect 1-2-3
1. Create Access Token(s) in ProductBoard > Settings > Integrations page (https://YOURSITE.productboard.com/settings/integrations). ![image](https://user-images.githubusercontent.com/1187448/115971445-5aae8500-a4fd-11eb-817c-dea57b17fce2.png)
2. Use `/pb configure --access-token SOME --gdpr-token OTHER` command in Mattermost to connect your ProductBoard account. You should see output similar to ![image](https://user-images.githubusercontent.com/1187448/115971551-e32d2580-a4fd-11eb-986e-176c49f65216.png)
3. You are ready to use ProductBoard Notes from within Mattermost!

### Create ProductBoard Note

##### Use `/pb create note` Command
- `--title`, `--content`, `--email`, and `--tags` map onto the Note fields
- Use quotes or backticks for values with spaces
- Use a comma-separated list for tags
- Use `--interactive` to finish filling out the inputs in a modal

##### Use `Create a ProductBoard Note` post menu item
![image](https://user-images.githubusercontent.com/1187448/115971856-c7c31a00-a4ff-11eb-830b-29e39fe02c39.png)
