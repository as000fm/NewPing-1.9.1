# NewPing-1.9.1
This is a copy for [XOD](https://xod.io/) patches of **[Tim Eckel's NewPing Library - v1.9.1 - 07/15/2018](https://bitbucket.org/teckel12/arduino-new-ping/wiki/Home)**

How to use in a **XOD patch**:

````
#pragma XOD error_raise enable

#pragma XOD require "https://github.com/as000fm/NewPing-1.9.1"

{{#global}}
#include <NewPing.h>
{{/global}}

struct State {
};

{{ GENERATED_CODE }}

void evaluate(Context ctx) {
    //auto inValue = getValue<input_IN>(ctx);
    //emitValue<output_OUT>(ctx, inValue);
}
````
