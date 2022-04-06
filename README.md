# PostgreSQL
Crud postgresSQL menggunakan bahasa pemrograman python dalam 1 file
menggunakan tabel
("""
                CREATE TABLE mahasiswa
                (
                    idmhs serial primary key,
                    nim varchar(10) unique not null,
                    nama varchar(50) not null,
                    idfakultas integer not null,
                    idprodi integer not null
                    )
                    """)
