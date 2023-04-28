# node-deploy


How to create project


MKDIR NODE-DEPLOY

NPM INIT -Y

NPM INSTALL -D TYPSCRIPT @TYPES/NODE TSX TSUP

NPX TSC —INIT


Change in TSCONFIG.json:   “target”: “es2016” -> “target”: “es2020” 

NPM I FASTIFY

NPM I PRISMA -D

NPM I @PRISMA/CLIENT

NPX PRISMA INIT

NPX PRISMA MIGRATE DEV


// To show Database 

NPX PRISMA STUDIO

// Create Validate Fields

NPM I ZOD
