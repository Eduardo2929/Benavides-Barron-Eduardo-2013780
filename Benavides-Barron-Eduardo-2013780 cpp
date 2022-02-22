#include <iostream>
using namespace std;

int opcion;
int b, cita, hora, minuto;
char nombre[50], descripcion [4000];

int main()
{

    while (1 == 1) {

        std::cout << "Le Damos la Bienvenida al Consultorio 'Buena Salud'\n";
        std::cout << "¿Que es lo que desea elegir?\n";
        cout << "1 Agendar Cita" << endl;
        cout << "2 Modificar Cita" << endl;
        cout << "3 Eliminar Cita" << endl;
        cout << "4 Lista de Citas Vigentes" << endl;
        cout << "5 Limpiar Pantalla" << endl;
        cout << "6 Salida del Sistema" << endl;
        cin >> opcion;

        //Modo Switch
        switch (opcion)
        {
        case 1:
            //Agendar una Cita
            cout << "\nSe Agendara una Cita, en un momento se la preparamos...\n\n";
            system("pause");
            cout << "\n\nInformacion recolectada, usted desea agendar una Cita, por favor, eliga un numero disponible a su gusto\n";
            cin >> cita;
            cout << "\n\nNumero disponible, por favor ingrese el nombre del usuario\n";
            cin >> nombre;
            cin.getline(nombre, 50);
            cout << "\n\nPor favor, ingrese la hora del tratamiento correspondiente a las horas abiertas del consultorio (24hrs)\n";
            cin >> hora;
            cout << "Ahora escriba a los minutos que se haria el tratamiento (Puede ser 00 en punto, o 30 hora y media)\n";
            cin >> minuto;
            cout << "\n\nHaga favor de escribir en la descripcion que es lo que necesita\n";
            cin >> descripcion;
            cin.getline(descripcion, 4000);
            cout << "\nEso seria todo por ahora, muchas gracias por su atencion!\nRegresando a la pantalla de inicio...";
            system("pause");
            break;

        case 2:
            //Modificar una Cita
            cout << "\nUsted desea Modificar una Cita existente, en un momento se lo preparamos...\n\n";
            system("pause");
            cout << "\nInformacion recolectada, usted desea modificar una cita existente\nFavor de escribir el numero de cita\n";
            cin >> cita;
            cout << "\nEspere un momento...\n";
            system("pause");
            cout << "\n\nCita encontrada! Entonces se realizaran los cambios al orden en que se agendo\n\n";
            system("pause");
            cout << "\n\nPor favor, ingrese el nombre del usuario\n";
            cin >> nombre;
            cin.getline(nombre, 50);
            cout << "\n\nPor favor, ingrese la hora del tratamiento correspondiente a las horas abiertas del consultorio (24hrs)\n";
            cin >> hora;
            cout << "Ahora escriba a los minutos que se haria el tratamiento (Puede ser 00 en punto, o 30 hora y media)\n";
            cin >> minuto;
            cout << "\n\nHaga favor de escribir en la descripcion que es lo que necesita\n";
            cin >> descripcion;
            cin.getline(descripcion, 4000);
            cout << "\nEso seria todo por ahora, muchas gracias por su atencion!\nRegresando a la pantalla de inicio...";
            system("pause");
            break;
            
        case 3:
            //Eliminar una Cita
            cout << "\nUsted desear eliminar una cita existente, espere un momento...\n\n";
            system("pause");
            cout << "\nPor favor, introduzca el numero de la cita que usted desea elimianr\n";
            cin >> cita;
            cout << "\n\nCita localizada\n";
            cout << "Realmente usted desea eliminar esta cita?";
            cout << "\n1 Si";
            cout << "\n2 No\n\n\n";
            cin >> b;
            if (b == 1)
            {
                cout << "Entendido, eleminando cita... \n";
                system("pause");
                cout << "Cita Eliminda, Que tenga un buen dia! :)\n";
                system("pause");
                break;
            }
            else
            {
                cout << "\nCita no eliminada, volviendo a la pantalla de inicio...\n\n";
                system("pause");
                break;
            }
        case 4:
            //Lista de Citas Vigentes
            cout << "\nHubo un error en el programa, por favor, vuelva a intentar mas tarde :c\n\n";
            break;
        case 5:
            //Limpiar Pantalla
            cout << "\nHubo un error en el programa, por favor, vuelva a intentar mas tarde :c\n\n";
            break;
        case 6:
            //Salida
            cout << "¿Esta seguro que quiere salir del Sistema?\n";
            cout << "\n1 Si";
            cout << "\n2 No\n\n\n";
            cin >> b;
            if (b == 1)
            {
                cout << "Entendido, apagando sistema... \n";
                cout << "Que tenga un buen dia! \n";
                exit(EXIT_SUCCESS);
            }
            else
            {
                cout << "\nPresione cualquier tecla para volver a la pantalla de Inicio\n\n";
                break;
            }
        default:
            cout << "\nLa opcion elegida no es valida, favor de elegir una opcion dentro del rango 1-6\n\n";
            break;
        }

    }
}

// Ejecutar programa: Ctrl + F5 o menú Depurar > Iniciar sin depurar
// Depurar programa: F5 o menú Depurar > Iniciar depuración

// Sugerencias para primeros pasos: 1. Use la ventana del Explorador de soluciones para agregar y administrar archivos
//   2. Use la ventana de Team Explorer para conectar con el control de código fuente
//   3. Use la ventana de salida para ver la salida de compilación y otros mensajes
//   4. Use la ventana Lista de errores para ver los errores
//   5. Vaya a Proyecto > Agregar nuevo elemento para crear nuevos archivos de código, o a Proyecto > Agregar elemento existente para agregar archivos de código existentes al proyecto
//   6. En el futuro, para volver a abrir este proyecto, vaya a Archivo > Abrir > Proyecto y seleccione el archivo .sln
