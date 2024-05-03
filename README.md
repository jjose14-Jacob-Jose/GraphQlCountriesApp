# Countries App with Kotlin and GraphQL

## Disclaimer
1. This application is developed by forking the [GitHub repo](https://github.com/philipplackner/GraphQlCountriesApp) and following the [YouTube tutorial](https://www.youtube.com/watch?v=ME3LH2bib3g)l of [Philipp Lackner](https://github.com/philipplackner).
2. The application hits API by [ApolloGraphQL](https://studio.apollographql.com/public/countries/variant/current/home).

### Prerequisites
1. [Android Studio](https://developer.android.com/studio)

### Installation 
1. Clone the GitHub repo: ```git clone git@github.com:jjose14-Jacob-Jose/GraphQlCountriesApp.git```
2. Open the project in Android Studio. Ensure you have GraphQL plugin installed. 
3. Click on 'Run' in Android Studio.

### Troubleshooting

### Setting up a virtual Android Device 
[Click here](https://developer.android.com/studio/run/managing-avds) for the steps to setup an Android Virtual Device on your Android Studio.

#### Use following command to load Countries GraphQL
In Android Studio Terminal, run the command ```./gradlew :app:downloadApolloSchema --endpoint='https://countries.trevorblades.com/graphql' --schema=app/src/main/graphql/com/plcoding/schema.graphqls``` (Terminal must be in the directory root).
 

