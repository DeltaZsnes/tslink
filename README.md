# tslink

// npm link
// npm link tslink

import helper1 from "tslink/helper1"
import { helper2, helper3 } from "tslink"
import * as h3 from "tslink/helper3"

console.log(helper1);
console.log(helper2)
const { print } = helper2;
console.log(print)

console.log(h3);
