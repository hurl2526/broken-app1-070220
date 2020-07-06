error first handling on passport.js

added async to register method of usercontroller as well as req.body instead of just body.

added user.profile.name to update profile method

capital p in updatePassword

brought in these on the user model: 
const Schema = mongoose.Schema
const bcrypt = require('bcryptjs')
require('dotenv').config()

as well as module.exports = mongoose.model('user', UserSchema)

router.post got rid of local- added it to path

added a catch to router.put

added main/home to index.js

added a .env

added s to process.env in app.js

not sure if you said there would be bugs in the views, only thing i noticed was that 
there is no image folder, not sure if thats a bug or just because we added that later