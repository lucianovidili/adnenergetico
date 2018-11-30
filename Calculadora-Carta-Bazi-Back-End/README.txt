//DONE -- Signo - - Afuera - - Pilar del A�o
//Fuciona para clientes nacidos entre el año 1901 y el 2043 inclusive.
func GetEnvoltura(fechaNac time.Time) string

//DONE - - Adentro - - Pilar del D�a
func GetTronco(fechaNac time.Time) string

//FALTA (algo hecho) - - Autoridad - - Pilar del Mes - - (El c�lculo es aproximado!. Se obtuvo del libro de mam�)
func GetDefensa(fechaNac time.Time) string

//DONE - - Ascendente - - Pilar de la Hora
func GetPoder(fechaNac time.Time) string