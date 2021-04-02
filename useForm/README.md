# useForm

Ejemplo de uso:
```
    const initialForm = {
        name: '',
        age: 0,
        email: ''
    };

    const [ form, handleInputChange, reset ] = useForm(initialForm);
```