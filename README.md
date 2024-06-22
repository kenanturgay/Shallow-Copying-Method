# Shallow-Copying-Method
Shallow copying means creating a copy of an object where only the first level of the object is copied. Any nested objects within the original object still reference the same objects as those in the original.


setForm ((prevState)=>({...prevState, [name]:value}));

