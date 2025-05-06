# Los graficos tardar en cargar, en especial los de dispersión, por favor no piense que no den, para reducir el tiempo de carga, realice el siguiente cambio en la linea N°11
            allData = parsed.data.filter(d => d.Country_Region).slice(0, 499);
