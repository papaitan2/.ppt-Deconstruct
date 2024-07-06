# .ppt-Deconstruct
Dump a PowerPoint file In its Slides , Objects and properties into a json To later be able to modify and rebuild it programmatically

# still in progress ()




![Captura de pantalla 2024-06-29 145749](https://github.com/papaitan2/.ppt-Deconstruct/assets/78953509/b7826b40-a747-47ab-8de6-17e806ab4c3e)


↑↑↑↑   yesterday at this stage
🌶️

JSON output example :


```json
{
    "Presentation": {
        "core_properties": {
            "author": "rama",
            "category": "",
            "comments": "",
            "content_status": "",
            "created": "2015-11-06T16:35:16",
            "identifier": "",
            "keywords": "",
            "language": "",
            "last_printed": null,
            "modified": "2024-07-06T05:21:14",
            "revision": 21,
            "subject": "",
            "title": "Protocolo VNC    Conexión Inversa",
            "version": ""
        },
        "slide_height": 6858000,
        "slide_width": 12192000
    },
    "Diapositiva_1": {
        "numero_diapositiva": 1,
        "formas": [
            {
                "tipo": 14,
                "tipo2": "PLACEHOLDER",
                "nombre": "Título 1",
                "shape_id": 2
            },
            {
                "tipo": 13,
                "tipo2": "PICTURE",
                "nombre": "Imagen 3",
                "shape_id": 4,
                "auto_shape_type": null,
                "is_placeholder": false,
                "height": 3381375,
                "width": 5876925,
                "left": 1004935,
                "top": 543208,
                "rotation": 0.0,
                "shadow": null,
                "click_action": {
                    "action_type": 0,
                    "target_slide": null,
                    "hyperlink": null
                }
            },
            {
                "tipo": 19,
                "tipo2": "TABLE",
                "nombre": "Tabla 4",
                "shape_id": 5,
                "auto_shape_type": null,
                "is_placeholder": false,
                "height": 2775585,
                "width": 4546600,
                "left": 6881860,
                "top": 3878544,
                "rotation": 0.0
            },
            {
                "tipo": 13,
                "tipo2": "PICTURE",
                "nombre": "Imagen 5",
                "shape_id": 6,
                "auto_shape_type": null,
                "is_placeholder": false,
                "height": 2200582,
                "width": 1381318,
                "left": 7773842,
                "top": 693687,
                "rotation": 0.0,
                "shadow": null,
                "click_action": {
                    "action_type": 0,
                    "target_slide": null,
                    "hyperlink": null
                }
            },
        ],
        "tablas": [
            {
                "first_col": false,
                "first_row": false,
                "horz_banding": false,
                "vert_banding": false,
                "filas": [
                    {
                        "height": 209550
                    },
                    {
                        "height": 609600
                    },
                    {
                        "height": 190500
                    },
                    {
                        "height": 190500
                    },
                    {
                        "height": 190500
                    },
                    {
                        "height": 190500
                    },
                    {
                        "height": 190500
                    },
                    {
                        "height": 190500
                    },
                    {
                        "height": 190500
                    },
                    {
                        "height": 200025
                    }
                ],
                "columnas": [
                    {
                        "width": 1776759
                    },
                    {
                        "width": 901071
                    },
                    {
                        "width": 828097
                    },
                    {
                        "width": 1040673
                    }
                ],
                "celdas": [
                    {
                        "text": " ",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "DEGRADACION",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 4,
                        "is_merge_origin": true,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "",
                        "margin_left": 91440,
                        "margin_right": 91440,
                        "margin_top": 45720,
                        "margin_bottom": 45720,
                        "vertical_anchor": null,
                        "is_merge_origin": false,
                        "is_spanned": true,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "",
                        "margin_left": 91440,
                        "margin_right": 91440,
                        "margin_top": 45720,
                        "margin_bottom": 45720,
                        "vertical_anchor": null,
                        "is_merge_origin": false,
                        "is_spanned": true,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "ACTIVOS  :",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "Fallo comunicación",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "Fallo suministro",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "Ransomware",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "Servidor ",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 4,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "3",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "2",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "4",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "Software",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 4,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "4",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "3",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "5",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "Router",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 4,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "3",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "2",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "4",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "BBDD",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 4,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "4",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "3",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "5",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "Conexión a internet",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 4,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "3",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "2",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "4",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "Servicio de correo electrónico",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 4,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "2",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "1",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "3",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "Instalación Eléctrica oficina",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 4,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "3",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "2",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "4",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "Oficina (Instalaciones fisicas)",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 4,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "4",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "3",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    },
                    {
                        "text": "5",
                        "margin_left": 9525,
                        "margin_right": 9525,
                        "margin_top": 9525,
                        "margin_bottom": 0,
                        "vertical_anchor": 3,
                        "is_merge_origin": false,
                        "is_spanned": false,
                        "fill": null,
                        "text_frame": {
                            "paragraphs": 1,
                            "word_wrap": null
                        }
                    }
                ]
            }
        ],
        "background": 5,
        "follow_master_background": false,
        "has_notes_slide": false,
        "name": "",
        "slide_id": 256
    },
    "Diapositiva_2": {
        "numero_diapositiva": 2,
        "formas": [
            {
                "tipo": 14,
                "tipo2": "PLACEHOLDER",
                "nombre": "Título 1",
                "shape_id": 2
            },
            {
                "tipo": 1,
                "tipo2": "AUTO_SHAPE",
                "nombre": "Rectángulo 6",
                "shape_id": 7,
                "auto_shape_type": null,
                "is_placeholder": false,
                "height": 3970318,
                "width": 11804073,
                "left": -1,
                "top": 1567979,
                "rotation": 0.0,
                "shadow": null,
                "fill": null,
                "line": 0,
                "texto": "VNC Virtual Network Computing, es un programa de software libre, basado en una estructura cliente-servidor.\n\nLa aplicación VNC fue desarrollada en el laboratorio de investigación de Olivetti, en el reino unido, el código fuente original es un código abierto con licencia pública.\n\nEs un sistema que permite compartir nuestro equipo de forma gráfica, \npara poder conectar remotamente con otro ordenador.\n\n",
                "alineacion": null,
                "font": {
                    "nombre": null,
                    "tamaño": 304800,
                    "negrita": null,
                    "cursiva": null
                },
                "click_action": {
                    "action_type": 0,
                    "target_slide": null,
                    "hyperlink": null
                }
            }
        ],
        "tablas": [],
        "background": 5,
        "follow_master_background": false,
        "has_notes_slide": false,
        "name": "",
        "slide_id": 257
    },
    "Diapositiva_3": {
        "numero_diapositiva": 3,
        "formas": [
            {
                "tipo": 1,
                "tipo2": "AUTO_SHAPE",
                "nombre": "Rectángulo 3",
                "shape_id": 4,
                "auto_shape_type": null,
                "is_placeholder": false,
                "height": 6370975,
                "width": 11658600,
                "left": 0,
                "top": 757766,
                "rotation": 0.0,
                "shadow": null,
                "fill": null,
                "line": 0,
                "texto": "El sistema VNC consiste en un cliente, un servidor y un protocolo de comunicación.\n\nEl VNC servidor es el programa en el equipo que comparte su pantalla.\n\nEl VNC cliente es el programa que vigila, controla e interactúa con el \tservidor (el cliente controla al servidor).\n\nEl VNC protocolo (RFB) es un sencillo protocolo de acceso remoto a \tinterfaces gráficas de usuario. Funciona: colocando un pixel en la \tposición X,Y especificada y mensajes de eventos desde el cliente al \tservidor.\n\n\n\n\n ",
                "alineacion": null,
                "font": {
                    "nombre": null,
                    "tamaño": 304800,
                    "negrita": null,
                    "cursiva": null
                },
                "click_action": {
                    "action_type": 0,
                    "target_slide": null,
                    "hyperlink": null
                }
            }
        ],
        "tablas": [],
        "background": 5,
        "follow_master_background": false,
        "has_notes_slide": false,
        "name": "",
        "slide_id": 258
    },
    "Diapositiva_4": {
        "numero_diapositiva": 4,
        "formas": [
            {
                "tipo": 1,
                "tipo2": "AUTO_SHAPE",
                "nombre": "Rectángulo 3",
                "shape_id": 4,
                "auto_shape_type": null,
                "is_placeholder": false,
                "height": 7109639,
                "width": 11700164,
                "left": 0,
                "top": 383335,
                "rotation": 0.0,
                "shadow": null,
                "fill": null,
                "line": 0,
                "texto": "El servidor para transmitir su pantalla al viewer debe dar \nsu IP y abrir determinados puertos, en nuestro caso usaremos los predeterminados que son los puertos 5900, 5800 o 5500.\n\n5900: En el método normal de operación, un viewer  se conecta con el servidor mediante este puerto, para abrir este puerto se debe configurar el firewall en el PC del servidor.\n\n5800: Si el viewer no posee el software necesario puede conectarse mediante un navegador, escribiendo por ejemplo la siguiente URL http://192.168.1.103:5800 \n\n5500: Este puerto se usa para la conexión en modo inverso, donde el encargado de abrirlo es el viewer y luego queda a la escucha. Entonces el servidor indica la IP del PC donde el viewer esta escuchando y se logra una conexión exitosa de forma que no es necesaria la excepción en el firewall\n\n",
                "alineacion": null,
                "font": {
                    "nombre": null,
                    "tamaño": 355600,
                    "negrita": null,
                    "cursiva": null
                },
                "click_action": {
                    "action_type": 0,
                    "target_slide": null,
                    "hyperlink": null
                }
            }
        ],
        "tablas": [],
        "background": 5,
        "follow_master_background": false,
        "has_notes_slide": false,
        "name": "",
        "slide_id": 259
    },
    "Diapositiva_5": {
        "numero_diapositiva": 5,
        "formas": [
            {
                "tipo": 1,
                "tipo2": "AUTO_SHAPE",
                "nombre": "Rectángulo 3",
                "shape_id": 4,
                "auto_shape_type": null,
                "is_placeholder": false,
                "height": 3108543,
                "width": 10806545,
                "left": 827314,
                "top": 1935401,
                "rotation": 0.0,
                "shadow": null,
                "fill": null,
                "line": 0,
                "texto": "Como ya se dijo hay varios programas con el protocolo VNC, cada uno con sus características de transmisión.\n\nEl software utilizado por nuestro grupo fue el tightVNC, de código abierto, como su nombre lo dice \"codificación apretada\", mejora el rendimiento en conexiones de bajo ancho de banda.",
                "alineacion": null,
                "font": {
                    "nombre": null,
                    "tamaño": 355600,
                    "negrita": null,
                    "cursiva": null
                },
                "click_action": {
                    "action_type": 0,
                    "target_slide": null,
                    "hyperlink": null
                }
            }
        ],
        "tablas": [],
        "background": 5,
        "follow_master_background": false,
        "has_notes_slide": false,
        "name": "",
        "slide_id": 260
    },
    "Diapositiva_6": {
        "numero_diapositiva": 6,
        "formas": [
            {
                "tipo": 13,
                "tipo2": "PICTURE",
                "nombre": "Imagen 3",
                "shape_id": 4,
                "auto_shape_type": null,
                "is_placeholder": false,
                "height": 6854653,
                "width": 12192000,
                "left": 0,
                "top": 1673,
                "rotation": 0.0,
                "shadow": null,
                "click_action": {
                    "action_type": 0,
                    "target_slide": null,
                    "hyperlink": null
                }
            }
        ],
        "tablas": [],
        "background": 5,
        "follow_master_background": false,
        "has_notes_slide": false,
        "name": "",
        "slide_id": 261
    },
    "Diapositiva_7": {
        "numero_diapositiva": 7,
        "formas": [
            {
                "tipo": 14,
                "tipo2": "PLACEHOLDER",
                "nombre": "Título 1",
                "shape_id": 2
            },
            {
                "tipo": 14,
                "tipo2": "PLACEHOLDER",
                "nombre": "Marcador de texto 2",
                "shape_id": 3
            },
            {
                "tipo": 13,
                "tipo2": "PICTURE",
                "nombre": "Imagen 3",
                "shape_id": 4,
                "auto_shape_type": null,
                "is_placeholder": false,
                "height": 6854653,
                "width": 12192000,
                "left": 0,
                "top": 1673,
                "rotation": 0.0,
                "shadow": null,
                "click_action": {
                    "action_type": 0,
                    "target_slide": null,
                    "hyperlink": null
                }
            }
        ],
        "tablas": [],
        "background": 5,
        "follow_master_background": false,
        "has_notes_slide": false,
        "name": "",
        "slide_id": 262
    },
    "Diapositiva_8": {
        "numero_diapositiva": 8,
        "formas": [
            {
                "tipo": 14,
                "tipo2": "PLACEHOLDER",
                "nombre": "Título 1",
                "shape_id": 2
            },
            {
                "tipo": 14,
                "tipo2": "PLACEHOLDER",
                "nombre": "Marcador de texto 2",
                "shape_id": 3
            },
            {
                "tipo": 13,
                "tipo2": "PICTURE",
                "nombre": "Imagen 3",
                "shape_id": 4,
                "auto_shape_type": null,
                "is_placeholder": false,
                "height": 6854653,
                "width": 12192000,
                "left": 0,
                "top": 1673,
                "rotation": 0.0,
                "shadow": null,
                "click_action": {
                    "action_type": 0,
                    "target_slide": null,
                    "hyperlink": null
                }
            }
        ],
        "tablas": [],
        "background": 5,
        "follow_master_background": false,
        "has_notes_slide": false,
        "name": "",
        "slide_id": 263
    },
    "Diapositiva_9": {
        "numero_diapositiva": 9,
        "formas": [
            {
                "tipo": 14,
                "tipo2": "PLACEHOLDER",
                "nombre": "Título 1",
                "shape_id": 2
            },
            {
                "tipo": 1,
                "tipo2": "AUTO_SHAPE",
                "nombre": "Rectángulo 3",
                "shape_id": 4,
                "auto_shape_type": null,
                "is_placeholder": false,
                "height": 4247317,
                "width": 11861442,
                "left": 165279,
                "top": 1559957,
                "rotation": 0.0,
                "shadow": null,
                "fill": null,
                "line": 0,
                "texto": "No siempre VNC fue utilizado de forma correcta, por ejemplo los troyanos que son pequeños programas podían hacer conectar a la victima en un puerto de nosotros anteriormente abierto, realizar una conexión y permitirnos tomar el control de la máquina, uno de los más conocidos es el troyano Bifrost.\n\nPero supongamos que tenemos un familiar que no posee bastos conocimientos en informática, y no sabe abrir un puerto o configurar su firewall, entonces los papeles se invierten.\n\nEl servidor solo necesitará saber la dirección IP del viewer y éste será el que se quede esperando una solicitud de conexión.\n\nLa ventaja de este enfoque es que los ajustes complicados, redirección de puertos, configuración de firewall, las hace el viewer.\n\n\n",
                "alineacion": null,
                "font": {
                    "nombre": null,
                    "tamaño": null,
                    "negrita": null,
                    "cursiva": null
                },
                "click_action": {
                    "action_type": 0,
                    "target_slide": null,
                    "hyperlink": null
                }
            },
            {
                "tipo": 1,
                "tipo2": "AUTO_SHAPE",
                "nombre": "Rectangle 1",
                "shape_id": 6,
                "auto_shape_type": null,
                "is_placeholder": false,
                "height": 0,
                "width": 12192000,
                "left": 0,
                "top": 0,
                "rotation": 0.0,
                "shadow": null,
                "fill": 1,
                "line": 0,
                "texto": "Abre una ventana de línea de comandos, vete a tu carpeta favorita y escribevncviewer -listen. Dale al enter. Aparecerá en la barra de tareas un pequeño icono tal que así: ",
                "alineacion": 4,
                "font": {
                    "nombre": "Helvetica Neue Light",
                    "tamaño": 127000,
                    "negrita": false,
                    "cursiva": false
                },
                "click_action": {
                    "action_type": 0,
                    "target_slide": null,
                    "hyperlink": null
                }
            }
        ],
        "tablas": [],
        "background": 5,
        "follow_master_background": false,
        "has_notes_slide": false,
        "name": "",
        "slide_id": 264
    },
    "Diapositiva_10": {
        "numero_diapositiva": 10,
        "formas": [
            {
                "tipo": 1,
                "tipo2": "AUTO_SHAPE",
                "nombre": "Rectángulo 3",
                "shape_id": 4,
                "auto_shape_type": null,
                "is_placeholder": false,
                "height": 4524315,
                "width": 12003110,
                "left": 66004,
                "top": 565117,
                "rotation": 0.0,
                "shadow": null,
                "fill": null,
                "line": 0,
                "texto": "Las instrucciones para realizar una conexión inversa con VNC son las siguientes:\n\nEn el Viewer\nSe redirige el puerto 5500 en tu router a tu PC.\nSe descarga el ejecutable tightVNC  \nAbrir una ventana de línea de comandos, ir a la carpeta contenedora y escribir “vncviewer -listen. Aparecerá en la barra de tareas un pequeño icono.\n\n\nEn el Servidor\nDescargar tightVNC y extraer los archivos “WinVNC.exe y VNCHooks.dll”.\nEjecutar el “WinVNC.exe” introducir una contraseña y pulsar OK.\nAparecerá un icono en la barra de tareas, click derecho y seleccionar la opción Add New Client.\nIntroducir la IP o el nombre de tu router, obteniendo así el control del PC remoto.\n\n",
                "alineacion": null,
                "font": {
                    "nombre": null,
                    "tamaño": null,
                    "negrita": null,
                    "cursiva": null
                },
                "click_action": {
                    "action_type": 0,
                    "target_slide": null,
                    "hyperlink": null
                }
            },
            {
                "tipo": 13,
                "tipo2": "PICTURE",
                "nombre": "Imagen 4",
                "shape_id": 5,
                "auto_shape_type": null,
                "is_placeholder": false,
                "height": 345379,
                "width": 1749918,
                "left": 6350894,
                "top": 2349393,
                "rotation": 0.0,
                "shadow": null,
                "click_action": {
                    "action_type": 0,
                    "target_slide": null,
                    "hyperlink": null
                }
            },
            {
                "tipo": 13,
                "tipo2": "PICTURE",
                "nombre": "Imagen 5",
                "shape_id": 6,
                "auto_shape_type": null,
                "is_placeholder": false,
                "height": 1447619,
                "width": 1790476,
                "left": 9927308,
                "top": 4250655,
                "rotation": 0.0,
                "shadow": null,
                "click_action": {
                    "action_type": 0,
                    "target_slide": null,
                    "hyperlink": null
                }
            }
        ],
        "tablas": [],
        "background": 5,
        "follow_master_background": false,
        "has_notes_slide": false,
        "name": "",
        "slide_id": 265
    }
}


↑↑↑↑   today at this stage
🌶️


```


