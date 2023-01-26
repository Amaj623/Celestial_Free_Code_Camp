--
-- PostgreSQL database dump
--

-- Dumped from database version 12.9 (Ubuntu 12.9-2.pgdg20.04+1)
-- Dumped by pg_dump version 12.9 (Ubuntu 12.9-2.pgdg20.04+1)

SET statement_timeout = 0;
SET lock_timeout = 0;
SET idle_in_transaction_session_timeout = 0;
SET client_encoding = 'UTF8';
SET standard_conforming_strings = on;
SELECT pg_catalog.set_config('search_path', '', false);
SET check_function_bodies = false;
SET xmloption = content;
SET client_min_messages = warning;
SET row_security = off;

DROP DATABASE universe;
--
-- Name: universe; Type: DATABASE; Schema: -; Owner: freecodecamp
--

CREATE DATABASE universe WITH TEMPLATE = template0 ENCODING = 'UTF8' LC_COLLATE = 'C.UTF-8' LC_CTYPE = 'C.UTF-8';


ALTER DATABASE universe OWNER TO freecodecamp;

\connect universe

SET statement_timeout = 0;
SET lock_timeout = 0;
SET idle_in_transaction_session_timeout = 0;
SET client_encoding = 'UTF8';
SET standard_conforming_strings = on;
SELECT pg_catalog.set_config('search_path', '', false);
SET check_function_bodies = false;
SET xmloption = content;
SET client_min_messages = warning;
SET row_security = off;

SET default_tablespace = '';

SET default_table_access_method = heap;

--
-- Name: galaxy; Type: TABLE; Schema: public; Owner: freecodecamp
--

CREATE TABLE public.galaxy (
    galaxy_id integer NOT NULL,
    name character varying(15) NOT NULL,
    distance integer,
    height integer,
    galaxy_level integer
);


ALTER TABLE public.galaxy OWNER TO freecodecamp;

--
-- Name: moon; Type: TABLE; Schema: public; Owner: freecodecamp
--

CREATE TABLE public.moon (
    moon_id integer NOT NULL,
    name character varying(15) NOT NULL,
    crater_count integer,
    planet_id integer,
    weight integer
);


ALTER TABLE public.moon OWNER TO freecodecamp;

--
-- Name: planet; Type: TABLE; Schema: public; Owner: freecodecamp
--

CREATE TABLE public.planet (
    planet_id integer NOT NULL,
    name character varying(15) NOT NULL,
    ring_count integer,
    weight numeric,
    planet_desc text,
    has_moon boolean,
    star_id integer
);


ALTER TABLE public.planet OWNER TO freecodecamp;

--
-- Name: rockets; Type: TABLE; Schema: public; Owner: freecodecamp
--

CREATE TABLE public.rockets (
    name character varying(15) NOT NULL,
    rockets_id integer NOT NULL,
    rocket_uid integer NOT NULL
);


ALTER TABLE public.rockets OWNER TO freecodecamp;

--
-- Name: star; Type: TABLE; Schema: public; Owner: freecodecamp
--

CREATE TABLE public.star (
    star_id integer NOT NULL,
    name character varying(15) NOT NULL,
    is_dead boolean,
    galaxy_id integer,
    weight integer
);


ALTER TABLE public.star OWNER TO freecodecamp;

--
-- Data for Name: galaxy; Type: TABLE DATA; Schema: public; Owner: freecodecamp
--

INSERT INTO public.galaxy VALUES (1, 'Milky', NULL, NULL, NULL);
INSERT INTO public.galaxy VALUES (2, 'Orangey', NULL, NULL, NULL);
INSERT INTO public.galaxy VALUES (3, 'Spongey', NULL, NULL, NULL);
INSERT INTO public.galaxy VALUES (4, 'Husky', NULL, NULL, NULL);
INSERT INTO public.galaxy VALUES (5, 'Musky', NULL, NULL, NULL);
INSERT INTO public.galaxy VALUES (6, 'Musty', NULL, NULL, NULL);
INSERT INTO public.galaxy VALUES (7, 'Justy', NULL, NULL, NULL);
INSERT INTO public.galaxy VALUES (8, 'Husty', NULL, NULL, NULL);
INSERT INTO public.galaxy VALUES (9, 'Crusty', NULL, NULL, NULL);
INSERT INTO public.galaxy VALUES (10, 'Fluffy', NULL, NULL, NULL);
INSERT INTO public.galaxy VALUES (12, 'Nunny', NULL, NULL, NULL);
INSERT INTO public.galaxy VALUES (13, 'Poppy', NULL, NULL, NULL);
INSERT INTO public.galaxy VALUES (14, 'Moppy', NULL, NULL, NULL);
INSERT INTO public.galaxy VALUES (15, 'Pip', NULL, NULL, NULL);
INSERT INTO public.galaxy VALUES (16, 'Flip', NULL, NULL, NULL);
INSERT INTO public.galaxy VALUES (17, 'Bip', NULL, NULL, NULL);
INSERT INTO public.galaxy VALUES (18, 'Tip', NULL, NULL, NULL);
INSERT INTO public.galaxy VALUES (19, 'Trip', NULL, NULL, NULL);
INSERT INTO public.galaxy VALUES (20, 'Boop', NULL, NULL, NULL);
INSERT INTO public.galaxy VALUES (11, 'Hun', NULL, NULL, NULL);


--
-- Data for Name: moon; Type: TABLE DATA; Schema: public; Owner: freecodecamp
--

INSERT INTO public.moon VALUES (1, 'Urus', 3, 1, NULL);
INSERT INTO public.moon VALUES (2, 'Moonie', 2, 2, NULL);
INSERT INTO public.moon VALUES (3, 'boonie', 2, 3, NULL);
INSERT INTO public.moon VALUES (4, 'ooe', 2, 4, NULL);
INSERT INTO public.moon VALUES (5, 'P', 2, 5, NULL);
INSERT INTO public.moon VALUES (6, 'C', 2, 6, NULL);
INSERT INTO public.moon VALUES (7, 'V', 2, 7, NULL);
INSERT INTO public.moon VALUES (8, 'B', 2, 8, NULL);
INSERT INTO public.moon VALUES (9, 'A', 2, 9, NULL);
INSERT INTO public.moon VALUES (10, 'R', 2, 10, NULL);
INSERT INTO public.moon VALUES (11, 'C', 2, 11, NULL);
INSERT INTO public.moon VALUES (12, 'N', 2, 12, NULL);
INSERT INTO public.moon VALUES (13, 'M', 2, 13, NULL);
INSERT INTO public.moon VALUES (14, 'C', 2, 14, NULL);
INSERT INTO public.moon VALUES (15, 'PIP', 2, 15, NULL);
INSERT INTO public.moon VALUES (16, 'KIP', 2, 16, NULL);
INSERT INTO public.moon VALUES (17, 'KIT', 2, 17, NULL);
INSERT INTO public.moon VALUES (18, 'PIT', 2, 18, NULL);
INSERT INTO public.moon VALUES (19, 'MIT', 2, 19, NULL);
INSERT INTO public.moon VALUES (20, 'BIT', 2, 20, NULL);


--
-- Data for Name: planet; Type: TABLE DATA; Schema: public; Owner: freecodecamp
--

INSERT INTO public.planet VALUES (1, 'Earth', 1, 350, 'Big green earth', true, 1);
INSERT INTO public.planet VALUES (2, 'Barth', 1, 350, 'Big green earth', true, 2);
INSERT INTO public.planet VALUES (3, 'Mepfloon', 1, 450, 'Big green earth', true, 3);
INSERT INTO public.planet VALUES (4, 'Jups', 3, 120, 'Big blue sphere', false, 4);
INSERT INTO public.planet VALUES (5, 'Jups', 3, 120, 'Big red sphere', false, 5);
INSERT INTO public.planet VALUES (6, 'Yups', 3, 120, 'Big red sphere', false, 6);
INSERT INTO public.planet VALUES (8, 'Pops', 3, 120, 'Big green sphere', false, 8);
INSERT INTO public.planet VALUES (9, 'ops', 3, 120, 'Big green sphere', false, 9);
INSERT INTO public.planet VALUES (10, 'ops', 7, 120, 'Big orange sphere', false, 10);
INSERT INTO public.planet VALUES (11, 'ops', 7, 120, 'orange sphere', false, 11);
INSERT INTO public.planet VALUES (12, 'Tips', 7, 320, 'orange square', false, 12);
INSERT INTO public.planet VALUES (13, 'Kips', 7, 320, 'orange ball', false, 13);
INSERT INTO public.planet VALUES (14, 'Naps', 7, 520, 'orange ball', false, 14);
INSERT INTO public.planet VALUES (15, 'Baps', 7, 520, 'orange ball', false, 15);
INSERT INTO public.planet VALUES (16, 'Raps', 7, 520, 'orange ball', false, 16);
INSERT INTO public.planet VALUES (17, 'Raps', 7, 220, 'orange ball', false, 17);
INSERT INTO public.planet VALUES (18, 'Raps', 7, 220, 'orange ball', false, 18);
INSERT INTO public.planet VALUES (19, 'Maps', 9, 120, 'orange ball', false, 19);
INSERT INTO public.planet VALUES (20, 'Paps', 9, 120, 'orange ball', false, 20);
INSERT INTO public.planet VALUES (7, 'Paps', 9, 120, 'orange ball', false, 7);


--
-- Data for Name: rockets; Type: TABLE DATA; Schema: public; Owner: freecodecamp
--

INSERT INTO public.rockets VALUES ('rocket 1', 1, 1);
INSERT INTO public.rockets VALUES ('rocket 2', 2, 2);
INSERT INTO public.rockets VALUES ('rocket 3', 3, 3);


--
-- Data for Name: star; Type: TABLE DATA; Schema: public; Owner: freecodecamp
--

INSERT INTO public.star VALUES (1, 'Bun', false, 1, NULL);
INSERT INTO public.star VALUES (2, 'Fun', false, 2, NULL);
INSERT INTO public.star VALUES (3, 'Pun', false, 3, NULL);
INSERT INTO public.star VALUES (4, 'Gun', false, 4, NULL);
INSERT INTO public.star VALUES (5, 'Nun', false, 5, NULL);
INSERT INTO public.star VALUES (6, 'Mun', false, 6, NULL);
INSERT INTO public.star VALUES (8, 'Jun', true, 8, NULL);
INSERT INTO public.star VALUES (9, 'Jun', true, 9, NULL);
INSERT INTO public.star VALUES (10, 'Nun', true, 10, NULL);
INSERT INTO public.star VALUES (11, 'Fun', true, 11, NULL);
INSERT INTO public.star VALUES (12, 'Fun', true, 12, NULL);
INSERT INTO public.star VALUES (13, 'un', true, 13, NULL);
INSERT INTO public.star VALUES (14, 'unc', true, 14, NULL);
INSERT INTO public.star VALUES (15, 'Junc', true, 15, NULL);
INSERT INTO public.star VALUES (16, 'Punc', true, 16, NULL);
INSERT INTO public.star VALUES (17, 'Puh', true, 17, NULL);
INSERT INTO public.star VALUES (18, 'Huh', true, 18, NULL);
INSERT INTO public.star VALUES (19, 'Pomp', true, 19, NULL);
INSERT INTO public.star VALUES (20, 'Romp', true, 20, NULL);
INSERT INTO public.star VALUES (7, 'unc', true, 7, NULL);


--
-- Name: galaxy galaxy_id_unique; Type: CONSTRAINT; Schema: public; Owner: freecodecamp
--

ALTER TABLE ONLY public.galaxy
    ADD CONSTRAINT galaxy_id_unique UNIQUE (galaxy_id);


--
-- Name: galaxy galaxy_pkey; Type: CONSTRAINT; Schema: public; Owner: freecodecamp
--

ALTER TABLE ONLY public.galaxy
    ADD CONSTRAINT galaxy_pkey PRIMARY KEY (galaxy_id);


--
-- Name: moon moon_pkey; Type: CONSTRAINT; Schema: public; Owner: freecodecamp
--

ALTER TABLE ONLY public.moon
    ADD CONSTRAINT moon_pkey PRIMARY KEY (moon_id);


--
-- Name: planet planet_id_unique; Type: CONSTRAINT; Schema: public; Owner: freecodecamp
--

ALTER TABLE ONLY public.planet
    ADD CONSTRAINT planet_id_unique UNIQUE (planet_id);


--
-- Name: planet planet_pkey; Type: CONSTRAINT; Schema: public; Owner: freecodecamp
--

ALTER TABLE ONLY public.planet
    ADD CONSTRAINT planet_pkey PRIMARY KEY (planet_id);


--
-- Name: rockets rocket_id_unique; Type: CONSTRAINT; Schema: public; Owner: freecodecamp
--

ALTER TABLE ONLY public.rockets
    ADD CONSTRAINT rocket_id_unique UNIQUE (rockets_id);


--
-- Name: rockets rockets_pkey; Type: CONSTRAINT; Schema: public; Owner: freecodecamp
--

ALTER TABLE ONLY public.rockets
    ADD CONSTRAINT rockets_pkey PRIMARY KEY (rockets_id);


--
-- Name: star star_pkey; Type: CONSTRAINT; Schema: public; Owner: freecodecamp
--

ALTER TABLE ONLY public.star
    ADD CONSTRAINT star_pkey PRIMARY KEY (star_id);


--
-- Name: star star_weight_unique; Type: CONSTRAINT; Schema: public; Owner: freecodecamp
--

ALTER TABLE ONLY public.star
    ADD CONSTRAINT star_weight_unique UNIQUE (weight);


--
-- Name: moon weight_unique; Type: CONSTRAINT; Schema: public; Owner: freecodecamp
--

ALTER TABLE ONLY public.moon
    ADD CONSTRAINT weight_unique UNIQUE (weight);


--
-- Name: star fk_galaxy; Type: FK CONSTRAINT; Schema: public; Owner: freecodecamp
--

ALTER TABLE ONLY public.star
    ADD CONSTRAINT fk_galaxy FOREIGN KEY (galaxy_id) REFERENCES public.galaxy(galaxy_id);


--
-- Name: planet fk_star; Type: FK CONSTRAINT; Schema: public; Owner: freecodecamp
--

ALTER TABLE ONLY public.planet
    ADD CONSTRAINT fk_star FOREIGN KEY (star_id) REFERENCES public.star(star_id);


--
-- Name: moon moon_planet_id_fkey; Type: FK CONSTRAINT; Schema: public; Owner: freecodecamp
--

ALTER TABLE ONLY public.moon
    ADD CONSTRAINT moon_planet_id_fkey FOREIGN KEY (planet_id) REFERENCES public.planet(planet_id);


--
-- PostgreSQL database dump complete
--

