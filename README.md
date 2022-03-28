En est proyecto se da feedback al usuario al tener un input inválido, cambiando el atributo class dinámicamente con el uso de plantilla en JSX.
Por ejemplo: <div className={`${styles['form-control']} ${!isValid && styles.invalid}`}>
  
Se elimina y/o agrega un elemento de un array dependiendo del estado de validación.
