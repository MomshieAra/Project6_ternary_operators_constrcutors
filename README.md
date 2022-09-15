# Project6_ternary_operators_constrcutors
const welcome = user => {
    const name = user && user.name ? user.name : "New User" ;
    return 'Welcome, ${name}';
}

console.log(welcome({name: 'Subin'})); // Welcome, Subin
console.log(welcome({})); // Welcome, New User
console.log(welcome()); // Welcome, New User
console.log(welcome(null)); // Welcome, New User

