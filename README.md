# What is this?

Implement the  perfect routing for the beginner.

# Installation

`npm i routing-handler --save`

Then...

...

import {HandleRoutes} from "routing-handler";

<Suspense fallback={<div>Loading....</div>}>

    {
        HandleRoutes(
        authenticated,
            ls.get('token'),
        Main,
        Auth,
        privateRoutes,
        authRoutes,
        '/dashboard',
        '/login')
    }
</Suspense>
...

## Uses

For Dynamically routing.


