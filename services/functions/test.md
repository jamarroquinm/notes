

npx aws-api-gateway-cli-test \
--username='admin@example.com' \
--password='Passw0rd!' \
--user-pool-id='us-east-1_kxHn2tNyD' \
--app-client-id='fiaama88qop4qt7cc2b16edic' \
--cognito-region='us-east-1' \
--identity-pool-id='us-east-1:df39382a-5227-48a1-afed-ea621efeb1bd' \
--invoke-url='https://8dkfw9pa52.execute-api.us-east-1.amazonaws.com' \
--api-gateway-region='us-east-1' \
--path-template='/notes' \
--method='POST' \
--body='{"content":"hello world","attachment":"hello.jpg"}'