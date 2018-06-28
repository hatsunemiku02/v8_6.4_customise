# v8_6.4_customise
just a v8 study , try to insert some code when v8 generate interpretor's byte code, 
the inserted code can be used to caculate v8 bytecode operations and break endless cycles

TODO:1. seperate bytecode generate state ,and add foo's to execute v8 bytecode.
     2. change the time to insert byte code from bytecode generate stage to somewhere else.
	 3. change inserted callruntime to a new customied bytecode that won't write the accumulator
