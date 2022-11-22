# Estudio Cactus Fullstack Test

This is a test to validate the knowledge of the candidates for the position of fullstack developer at Estudio Cactus

## Stack

- React
- NextJS
- Firebase
- Tailwindcss

## Description

In this case the test consists of creating a 3d room configurator. In the following link you can see an example of how the configurator should look like: https://app.estudiocactus.com/visualizer.mp4

Following you have a detailed layout of the data needed to pass the test:

Base image url: https://firebasestorage.googleapis.com/v0/b/visualizer-new-devs-test.appspot.com/o/base.jpeg?alt=media&token=358ccdea-3cf9-4751-ae48-4631e4700554

Coordinates to draw the points over the base image:

```
.
└── firestore(/)
    └── points (collection)
```

List of all materials (TIP: You have to think about the right query to get all the materials for a specific point -> Firestore allows array-contains queries)

```
.
└── firestore(/)
    └── materials (collection)
```

The credentials for the Firebase connection are located at

```
.
└── firebase
    └── config
```

## Requirements

1. Use StandardJS as a linter
2. Code should be completely in english ( filenames, variables)

**IMPORTANT:** We won't accept code with harcoded databaes values (e.g. document id's to make comparisons, url's for background images etc)

## How to start?

1. Create a new repo using this one as a base(without forking)
2. Make at least 1 first commit with the original code, to see the init hour.
3. Make individiual commits for each block you create. The last commit marks the end.
4. Send us a link to your repo.
5. Deploy your repo to vercel.
6. Send us a link to the deployed project.

## What we value?

- Simplicity of the solution
- Organization and clean code
- Utilization of components
- Mobile first & RWD
- Git usage
- Web Performance Optimization
- Technical knowledge
- Layout knowledge (HTML5 y CSS3)
