> [!NOTE]
> Sponsored by the Open Source project Flagsmith https://github.com/Flagsmith/flagsmith

# HealthCheck

How friendly is your GitHub Open Source repo? This project will check to make sure you are using Best Practices to get more users, contributors and stars.

![Screenshot of repo checks](https://github.com/EddieHubCommunity/HealthCheck/assets/624760/2de03c3b-1d53-4edb-9f7e-f3ffd550e62b)

## Quickstart guide

1. Clone this GitHub repo
2. Install the dependencies with `npm ci`
3. Copy `.env.example` to `.env` (you will need an environment key from Flagsmith, this is shown later on)
4. Create a free account on Flagsmith https://www.flagsmith.com (you can also sign in with GitHub)
5. Create an Organisation and Project
6. Create the feature flags with these steps

   a. Create the feature `tagline` by clicking `Create Feature`

   ![Create feature screenshot](https://github.com/EddieHubCommunity/HealthCheck/assets/624760/20bcf62c-a4be-487c-80ee-f5d39bcafde6)

   b. Fill in the feature flag form with these details and click `Create Feature`

   ![Save feature flag screenshot](https://github.com/EddieHubCommunity/HealthCheck/assets/624760/f0399aae-2b2f-4e47-83e2-9d3d21797a42)

   c. (OPTIONAL) Import the flags to your Flagsmith account using the file `./flagsmith.json` (note this will be per environment, for example `development`)

   ![Import flags on Flagsmith](https://github.com/EddieHubCommunity/HealthCheck/assets/624760/f45351af-2013-4928-826a-c9dad33038a4)

7. Get your environment key from Flagsmith and add to `.env` file

![How to get environment key](https://github.com/EddieHubCommunity/HealthCheck/assets/624760/0fb56934-2d27-486a-9859-365672771407)

8. Run the project with `npm run dev`

---

TODO

- prisma
- go to github's api
- save api data
- make healthcheck and save results
- redirect to results page
