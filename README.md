# cards-against-your-friends
Cards Against your Friends, a websockets based clone of Cards Against HumanityⓇ https://cardsagainsthumanity.com/

The project is split into a single page UI written in Vue.js, and an API designed to execute in AWS Lambda behind a websockets API Gateway. Terraform to provision the AWS infrastructure is in the [ws-api/ci](ws-api/ci) directory.