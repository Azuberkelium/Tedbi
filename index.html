import React, { useState, useEffect } from 'react';
import ReactDOM from 'react-dom';
import { motion, AnimatePresence } from 'framer-motion';

// Data for all 118 elements of the periodic table
const elementsData = [
    { atomic_number: 1, symbol: 'H', name: 'Hydrogen', type: 'nonmetal', atomic_mass: 1.008, can_combine: true, description: 'The lightest element, essential for creating water and other compounds.', x: 1, y: 1 },
    { atomic_number: 2, symbol: 'He', name: 'Helium', type: 'noble_gas', atomic_mass: 4.0026, can_combine: false, description: 'A noble gas, very stable and unreactive.', x: 18, y: 1 },
    { atomic_number: 3, symbol: 'Li', name: 'Lithium', type: 'alkali_metal', atomic_mass: 6.94, can_combine: true, description: 'A soft, silvery-white alkali metal. Highly reactive.', x: 1, y: 2 },
    { atomic_number: 4, symbol: 'Be', name: 'Beryllium', type: 'alkaline_earth_metal', atomic_mass: 9.0122, can_combine: true, description: 'A lightweight, silvery metal. Used in alloys.', x: 2, y: 2 },
    { atomic_number: 5, symbol: 'B', name: 'Boron', type: 'metalloid', atomic_mass: 10.81, can_combine: true, description: 'A metalloid with diverse applications.', x: 13, y: 2 },
    { atomic_number: 6, symbol: 'C', name: 'Carbon', type: 'nonmetal', atomic_mass: 12.011, can_combine: true, description: 'The basis of all known life, forms countless compounds.', x: 14, y: 2 },
    { atomic_number: 7, symbol: 'N', name: 'Nitrogen', type: 'nonmetal', atomic_mass: 14.007, can_combine: true, description: 'A major component of Earth\'s atmosphere, essential for living organisms.', x: 15, y: 2 },
    { atomic_number: 8, symbol: 'O', name: 'Oxygen', type: 'nonmetal', atomic_mass: 15.999, can_combine: true, description: 'The element we breathe, highly reactive and crucial for many compounds.', x: 16, y: 2 },
    { atomic_number: 9, symbol: 'F', name: 'Fluorine', type: 'halogen', atomic_mass: 18.998, can_combine: true, description: 'The most reactive element, a highly electronegative halogen.', x: 17, y: 2 },
    { atomic_number: 10, symbol: 'Ne', name: 'Neon', type: 'noble_gas', atomic_mass: 20.18, can_combine: false, description: 'A noble gas, famous for its use in bright signs.', x: 18, y: 2 },
    { atomic_number: 11, symbol: 'Na', name: 'Sodium', type: 'alkali_metal', atomic_mass: 22.99, can_combine: true, description: 'A soft, silvery-white alkali metal. Highly reactive.', x: 1, y: 3 },
    { atomic_number: 12, symbol: 'Mg', name: 'Magnesium', type: 'alkaline_earth_metal', atomic_mass: 24.305, can_combine: true, description: 'A light, reactive metal.', x: 2, y: 3 },
    { atomic_number: 13, symbol: 'Al', name: 'Aluminum', type: 'post_transition_metal', atomic_mass: 26.982, can_combine: true, description: 'A lightweight, durable metal.', x: 13, y: 3 },
    { atomic_number: 14, symbol: 'Si', name: 'Silicon', type: 'metalloid', atomic_mass: 28.085, can_combine: true, description: 'A metalloid widely used in electronics.', x: 14, y: 3 },
    { atomic_number: 15, symbol: 'P', name: 'Phosphorus', type: 'nonmetal', atomic_mass: 30.974, can_combine: true, description: 'A nonmetal essential for life.', x: 15, y: 3 },
    { atomic_number: 16, symbol: 'S', name: 'Sulfur', type: 'nonmetal', atomic_mass: 32.06, can_combine: true, description: 'A plentiful nonmetal, with a distinctive smell.', x: 16, y: 3 },
    { atomic_number: 17, symbol: 'Cl', name: 'Chlorine', type: 'halogen', atomic_mass: 35.453, can_combine: true, description: 'A poisonous halogen, often used as a disinfectant.', x: 17, y: 3 },
    { atomic_number: 18, symbol: 'Ar', name: 'Argon', type: 'noble_gas', atomic_mass: 39.948, can_combine: false, description: 'A noble gas, the third most common gas in the atmosphere.', x: 18, y: 3 },
    { atomic_number: 19, symbol: 'K', name: 'Potassium', type: 'alkali_metal', atomic_mass: 39.098, can_combine: true, description: 'A soft silvery metal that oxidizes rapidly in air.', x: 1, y: 4 },
    { atomic_number: 20, symbol: 'Ca', name: 'Calcium', type: 'alkaline_earth_metal', atomic_mass: 40.078, can_combine: true, description: 'A soft gray alkaline earth metal.', x: 2, y: 4 },
    { atomic_number: 21, symbol: 'Sc', name: 'Scandium', type: 'transition_metal', atomic_mass: 44.956, can_combine: true, description: 'A soft, silvery-white transition metal.', x: 3, y: 4 },
    { atomic_number: 22, symbol: 'Ti', name: 'Titanium', type: 'transition_metal', atomic_mass: 47.867, can_combine: true, description: 'A lustrous transition metal with a silver color and low density.', x: 4, y: 4 },
    { atomic_number: 23, symbol: 'V', name: 'Vanadium', type: 'transition_metal', atomic_mass: 50.942, can_combine: true, description: 'A hard, silvery-grey, ductile transition metal.', x: 5, y: 4 },
    { atomic_number: 24, symbol: 'Cr', name: 'Chromium', type: 'transition_metal', atomic_mass: 51.996, can_combine: true, description: 'A steely-grey, lustrous, hard metal.', x: 6, y: 4 },
    { atomic_number: 25, symbol: 'Mn', name: 'Manganese', type: 'transition_metal', atomic_mass: 54.938, can_combine: true, description: 'A hard, brittle, silvery-white metal.', x: 7, y: 4 },
    { atomic_number: 26, symbol: 'Fe', name: 'Iron', type: 'transition_metal', atomic_mass: 55.845, can_combine: true, description: 'A metal that is a major component of steel.', x: 8, y: 4 },
    { atomic_number: 27, symbol: 'Co', name: 'Cobalt', type: 'transition_metal', atomic_mass: 58.933, can_combine: true, description: 'A hard, ferromagnetic, silver-white metal.', x: 9, y: 4 },
    { atomic_number: 28, symbol: 'Ni', name: 'Nickel', type: 'transition_metal', atomic_mass: 58.693, can_combine: true, description: 'A silvery-white lustrous metal with a slight golden tinge.', x: 10, y: 4 },
    { atomic_number: 29, symbol: 'Cu', name: 'Copper', type: 'transition_metal', atomic_mass: 63.546, can_combine: true, description: 'A soft, malleable, and ductile metal with very high thermal and electrical conductivity.', x: 11, y: 4 },
    { atomic_number: 30, symbol: 'Zn', name: 'Zinc', type: 'transition_metal', atomic_mass: 65.38, can_combine: true, description: 'A bluish-white lustrous metal.', x: 12, y: 4 },
    { atomic_number: 31, symbol: 'Ga', name: 'Gallium', type: 'post_transition_metal', atomic_mass: 69.723, can_combine: true, description: 'A soft, silvery-white metal at standard temperature and pressure.', x: 13, y: 4 },
    { atomic_number: 32, symbol: 'Ge', name: 'Germanium', type: 'metalloid', atomic_mass: 72.63, can_combine: true, description: 'A lustrous, hard, grayish-white metalloid.', x: 14, y: 4 },
    { atomic_number: 33, symbol: 'As', name: 'Arsenic', type: 'metalloid', atomic_mass: 74.922, can_combine: true, description: 'A poisonous metalloid.', x: 15, y: 4 },
    { atomic_number: 34, symbol: 'Se', name: 'Selenium', type: 'nonmetal', atomic_mass: 78.971, can_combine: true, description: 'A nonmetal.', x: 16, y: 4 },
    { atomic_number: 35, symbol: 'Br', name: 'Bromine', type: 'halogen', atomic_mass: 79.904, can_combine: true, description: 'A reddish-brown liquid at room temperature.', x: 17, y: 4 },
    { atomic_number: 36, symbol: 'Kr', name: 'Krypton', type: 'noble_gas', atomic_mass: 83.798, can_combine: false, description: 'A noble gas.', x: 18, y: 4 },
    { atomic_number: 37, symbol: 'Rb', name: 'Rubidium', type: 'alkali_metal', atomic_mass: 85.468, can_combine: true, description: 'A soft, silvery-white metallic element.', x: 1, y: 5 },
    { atomic_number: 38, symbol: 'Sr', name: 'Strontium', type: 'alkaline_earth_metal', atomic_mass: 87.62, can_combine: true, description: 'A soft, silvery-white or yellowish metallic element.', x: 2, y: 5 },
    { atomic_number: 39, symbol: 'Y', name: 'Yttrium', type: 'transition_metal', atomic_mass: 88.906, can_combine: true, description: 'A soft, silvery-metallic, and lustrous transition metal.', x: 3, y: 5 },
    { atomic_number: 40, symbol: 'Zr', name: 'Zirconium', type: 'transition_metal', atomic_mass: 91.224, can_combine: true, description: 'A lustrous, grey-white, strong transition metal.', x: 4, y: 5 },
    { atomic_number: 41, symbol: 'Nb', name: 'Niobium', type: 'transition_metal', atomic_mass: 92.906, can_combine: true, description: 'A light-grey, crystalline, ductile transition metal.', x: 5, y: 5 },
    { atomic_number: 42, symbol: 'Mo', name: 'Molybdenum', type: 'transition_metal', atomic_mass: 95.95, can_combine: true, description: 'A silvery-white metallic element.', x: 6, y: 5 },
    { atomic_number: 43, symbol: 'Tc', name: 'Technetium', type: 'transition_metal', atomic_mass: 98, can_combine: true, description: 'The lightest element with no stable isotopes.', x: 7, y: 5 },
    { atomic_number: 44, symbol: 'Ru', name: 'Ruthenium', type: 'transition_metal', atomic_mass: 101.07, can_combine: true, description: 'A rare transition metal of the platinum group.', x: 8, y: 5 },
    { atomic_number: 45, symbol: 'Rh', name: 'Rhodium', type: 'transition_metal', atomic_mass: 102.91, can_combine: true, description: 'A rare, silvery-white, hard, and chemically inert transition metal.', x: 9, y: 5 },
    { atomic_number: 46, symbol: 'Pd', name: 'Palladium', type: 'transition_metal', atomic_mass: 106.42, can_combine: true, description: 'A rare and lustrous silvery-white metal.', x: 10, y: 5 },
    { atomic_number: 47, symbol: 'Ag', name: 'Silver', type: 'transition_metal', atomic_mass: 107.87, can_combine: true, description: 'A soft, white, lustrous transition metal.', x: 11, y: 5 },
    { atomic_number: 48, symbol: 'Cd', name: 'Cadmium', type: 'transition_metal', atomic_mass: 112.41, can_combine: true, description: 'A soft, malleable, ductile, bluish-white metal.', x: 12, y: 5 },
    { atomic_number: 49, symbol: 'In', name: 'Indium', type: 'post_transition_metal', atomic_mass: 114.82, can_combine: true, description: 'A soft, malleable, and easily fusible post-transition metal.', x: 13, y: 5 },
    { atomic_number: 50, symbol: 'Sn', name: 'Tin', type: 'post_transition_metal', atomic_mass: 118.71, can_combine: true, description: 'A malleable, ductile, highly crystalline post-transition metal.', x: 14, y: 5 },
    { atomic_number: 51, symbol: 'Sb', name: 'Antimony', type: 'metalloid', atomic_mass: 121.76, can_combine: true, description: 'A lustrous gray metalloid.', x: 15, y: 5 },
    { atomic_number: 52, symbol: 'Te', name: 'Tellurium', type: 'metalloid', atomic_mass: 127.6, can_combine: true, description: 'A brittle, mildly toxic, silvery-white metalloid.', x: 16, y: 5 },
    { atomic_number: 53, symbol: 'I', name: 'Iodine', type: 'halogen', atomic_mass: 126.9, can_combine: true, description: 'A lustrous, purple-black metallic solid at standard conditions.', x: 17, y: 5 },
    { atomic_number: 54, symbol: 'Xe', name: 'Xenon', type: 'noble_gas', atomic_mass: 131.29, can_combine: false, description: 'A heavy, colorless, odorless noble gas.', x: 18, y: 5 },
    { atomic_number: 55, symbol: 'Cs', name: 'Caesium', type: 'alkali_metal', atomic_mass: 132.91, can_combine: true, description: 'A very soft, silvery-gold metallic element.', x: 1, y: 6 },
    { atomic_number: 56, symbol: 'Ba', name: 'Barium', type: 'alkaline_earth_metal', atomic_mass: 137.33, can_combine: true, description: 'A soft, silvery metallic alkaline earth metal.', x: 2, y: 6 },
    { atomic_number: 57, symbol: 'La', name: 'Lanthanum', type: 'lanthanide', atomic_mass: 138.91, can_combine: true, description: 'A soft, ductile, silvery-white metallic element.', x: 3, y: 6 },
    { atomic_number: 58, symbol: 'Ce', name: 'Cerium', type: 'lanthanide', atomic_mass: 140.12, can_combine: true, description: 'A soft, ductile, silvery-white metallic element.', x: 4, y: 9 },
    { atomic_number: 59, symbol: 'Pr', name: 'Praseodymium', type: 'lanthanide', atomic_mass: 140.91, can_combine: true, description: 'A soft, silvery, malleable, and ductile lanthanide metal.', x: 5, y: 9 },
    { atomic_number: 60, symbol: 'Nd', name: 'Neodymium', type: 'lanthanide', atomic_mass: 144.24, can_combine: true, description: 'A soft, silvery metal.', x: 6, y: 9 },
    { atomic_number: 61, symbol: 'Pm', name: 'Promethium', type: 'lanthanide', atomic_mass: 145, can_combine: true, description: 'A radioactive lanthanide.', x: 7, y: 9 },
    { atomic_number: 62, symbol: 'Sm', name: 'Samarium', type: 'lanthanide', atomic_mass: 150.36, can_combine: true, description: 'A soft, silvery metal.', x: 8, y: 9 },
    { atomic_number: 63, symbol: 'Eu', name: 'Europium', type: 'lanthanide', atomic_mass: 151.96, can_combine: true, description: 'A silvery-white, ductile, and malleable lanthanide metal.', x: 9, y: 9 },
    { atomic_number: 64, symbol: 'Gd', name: 'Gadolinium', type: 'lanthanide', atomic_mass: 157.25, can_combine: true, description: 'A silvery-white, malleable, and ductile rare-earth metal.', x: 10, y: 9 },
    { atomic_number: 65, symbol: 'Tb', name: 'Terbium', type: 'lanthanide', atomic_mass: 158.93, can_combine: true, description: 'A silvery-white, rare-earth metal.', x: 11, y: 9 },
    { atomic_number: 66, symbol: 'Dy', name: 'Dysprosium', type: 'lanthanide', atomic_mass: 162.5, can_combine: true, description: 'A soft, silvery-white metal.', x: 12, y: 9 },
    { atomic_number: 67, symbol: 'Ho', name: 'Holmium', type: 'lanthanide', atomic_mass: 164.93, can_combine: true, description: 'A soft, malleable, silvery-white metal.', x: 13, y: 9 },
    { atomic_number: 68, symbol: 'Er', name: 'Erbium', type: 'lanthanide', atomic_mass: 167.26, can_combine: true, description: 'A soft, malleable, silvery metal.', x: 14, y: 9 },
    { atomic_number: 69, symbol: 'Tm', name: 'Thulium', type: 'lanthanide', atomic_mass: 168.93, can_combine: true, description: 'A soft, malleable, silvery-white metal.', x: 15, y: 9 },
    { atomic_number: 70, symbol: 'Yb', name: 'Ytterbium', type: 'lanthanide', atomic_mass: 173.05, can_combine: true, description: 'A soft, silvery-white, and malleable lanthanide metal.', x: 16, y: 9 },
    { atomic_number: 71, symbol: 'Lu', name: 'Lutetium', type: 'lanthanide', atomic_mass: 174.97, can_combine: true, description: 'A soft, silvery-white metal.', x: 17, y: 9 },
    { atomic_number: 72, symbol: 'Hf', name: 'Hafnium', type: 'transition_metal', atomic_mass: 178.49, can_combine: true, description: 'A lustrous, silvery, ductile transition metal.', x: 4, y: 6 },
    { atomic_number: 73, symbol: 'Ta', name: 'Tantalum', type: 'transition_metal', atomic_mass: 180.95, can_combine: true, description: 'A rare, hard, blue-gray, lustrous transition metal.', x: 5, y: 6 },
    { atomic_number: 74, symbol: 'W', name: 'Tungsten', type: 'transition_metal', atomic_mass: 183.84, can_combine: true, description: 'A rare metal on Earth, found naturally only in chemical compounds.', x: 6, y: 6 },
    { atomic_number: 75, symbol: 'Re', name: 'Rhenium', type: 'transition_metal', atomic_mass: 186.21, can_combine: true, description: 'A silvery-white metal.', x: 7, y: 6 },
    { atomic_number: 76, symbol: 'Os', name: 'Osmium', type: 'transition_metal', atomic_mass: 190.23, can_combine: true, description: 'A hard, brittle, bluish-white transition metal.', x: 8, y: 6 },
    { atomic_number: 77, symbol: 'Ir', name: 'Iridium', type: 'transition_metal', atomic_mass: 192.22, can_combine: true, description: 'A hard, brittle, silvery-white transition metal.', x: 9, y: 6 },
    { atomic_number: 78, symbol: 'Pt', name: 'Platinum', type: 'transition_metal', atomic_mass: 195.08, can_combine: true, description: 'A dense, malleable, ductile, highly unreactive, precious, silvery-white transition metal.', x: 10, y: 6 },
    { atomic_number: 79, symbol: 'Au', name: 'Gold', type: 'transition_metal', atomic_mass: 196.97, can_combine: true, description: 'A bright, slightly reddish yellow, dense, soft, malleable, and ductile metal.', x: 11, y: 6 },
    { atomic_number: 80, symbol: 'Hg', name: 'Mercury', type: 'transition_metal', atomic_mass: 200.59, can_combine: true, description: 'The only metallic element that is a liquid at standard conditions for temperature and pressure.', x: 12, y: 6 },
    { atomic_number: 81, symbol: 'Tl', name: 'Thallium', type: 'post_transition_metal', atomic_mass: 204.38, can_combine: true, description: 'A soft, malleable, bluish-white metal.', x: 13, y: 6 },
    { atomic_number: 82, symbol: 'Pb', name: 'Lead', type: 'post_transition_metal', atomic_mass: 207.2, can_combine: true, description: 'A soft, malleable, and easily fusible heavy metal.', x: 14, y: 6 },
    { atomic_number: 83, symbol: 'Bi', name: 'Bismuth', type: 'post_transition_metal', atomic_mass: 208.98, can_combine: true, description: 'A brittle, silvery-white metal.', x: 15, y: 6 },
    { atomic_number: 84, symbol: 'Po', name: 'Polonium', type: 'metalloid', atomic_mass: 209, can_combine: true, description: 'A rare and highly radioactive metalloid.', x: 16, y: 6 },
    { atomic_number: 85, symbol: 'At', name: 'Astatine', type: 'halogen', atomic_mass: 210, can_combine: true, description: 'A highly radioactive chemical element.', x: 17, y: 6 },
    { atomic_number: 86, symbol: 'Rn', name: 'Radon', type: 'noble_gas', atomic_mass: 222, can_combine: false, description: 'A radioactive, colorless, odorless, tasteless noble gas.', x: 18, y: 6 },
    { atomic_number: 87, symbol: 'Fr', name: 'Francium', type: 'alkali_metal', atomic_mass: 223, can_combine: true, description: 'A highly radioactive alkali metal.', x: 1, y: 7 },
    { atomic_number: 88, symbol: 'Ra', name: 'Radium', type: 'alkaline_earth_metal', atomic_mass: 226, can_combine: true, description: 'A radioactive alkaline earth metal.', x: 2, y: 7 },
    { atomic_number: 89, symbol: 'Ac', name: 'Actinium', type: 'actinide', atomic_mass: 227, can_combine: true, description: 'A radioactive metallic element.', x: 3, y: 7 },
    { atomic_number: 90, symbol: 'Th', name: 'Thorium', type: 'actinide', atomic_mass: 232.04, can_combine: true, description: 'A naturally radioactive metallic element.', x: 4, y: 10 },
    { atomic_number: 91, symbol: 'Pa', name: 'Protactinium', type: 'actinide', atomic_mass: 231.04, can_combine: true, description: 'A dense, silvery-gray metal.', x: 5, y: 10 },
    { atomic_number: 92, symbol: 'U', name: 'Uranium', type: 'actinide', atomic_mass: 238.03, can_combine: true, description: 'A heavy, silvery-white, radioactive metal.', x: 6, y: 10 },
    { atomic_number: 93, symbol: 'Np', name: 'Neptunium', type: 'actinide', atomic_mass: 237, can_combine: true, description: 'A hard, silvery, ductile, radioactive metal.', x: 7, y: 10 },
    { atomic_number: 94, symbol: 'Pu', name: 'Plutonium', type: 'actinide', atomic_mass: 244, can_combine: true, description: 'A radioactive element.', x: 8, y: 10 },
    { atomic_number: 95, symbol: 'Am', name: 'Americium', type: 'actinide', atomic_mass: 243, can_combine: true, description: 'A radioactive transuranic element.', x: 9, y: 10 },
    { atomic_number: 96, symbol: 'Cm', name: 'Curium', type: 'actinide', atomic_mass: 247, can_combine: true, description: 'A radioactive transuranic element.', x: 10, y: 10 },
    { atomic_number: 97, symbol: 'Bk', name: 'Berkelium', type: 'actinide', atomic_mass: 247, can_combine: true, description: 'A radioactive transuranic element.', x: 11, y: 10 },
    { atomic_number: 98, symbol: 'Cf', name: 'Californium', type: 'actinide', atomic_mass: 251, can_combine: true, description: 'A radioactive transuranic element.', x: 12, y: 10 },
    { atomic_number: 99, symbol: 'Es', name: 'Einsteinium', type: 'actinide', atomic_mass: 252, can_combine: true, description: 'A synthetic element.', x: 13, y: 10 },
    { atomic_number: 100, symbol: 'Fm', name: 'Fermium', type: 'actinide', atomic_mass: 257, can_combine: true, description: 'A synthetic element.', x: 14, y: 10 },
    { atomic_number: 101, symbol: 'Md', name: 'Mendelevium', type: 'actinide', atomic_mass: 258, can_combine: true, description: 'A synthetic element.', x: 15, y: 10 },
    { atomic_number: 102, symbol: 'No', name: 'Nobelium', type: 'actinide', atomic_mass: 259, can_combine: true, description: 'A synthetic element.', x: 16, y: 10 },
    { atomic_number: 103, symbol: 'Lr', name: 'Lawrencium', type: 'actinide', atomic_mass: 266, can_combine: true, description: 'A synthetic element.', x: 17, y: 10 },
    { atomic_number: 104, symbol: 'Rf', name: 'Rutherfordium', type: 'transition_metal', atomic_mass: 267, can_combine: true, description: 'A synthetic element.', x: 4, y: 7 },
    { atomic_number: 105, symbol: 'Db', name: 'Dubnium', type: 'transition_metal', atomic_mass: 268, can_combine: true, description: 'A synthetic element.', x: 5, y: 7 },
    { atomic_number: 106, symbol: 'Sg', name: 'Seaborgium', type: 'transition_metal', atomic_mass: 269, can_combine: true, description: 'A synthetic element.', x: 6, y: 7 },
    { atomic_number: 107, symbol: 'Bh', name: 'Bohrium', type: 'transition_metal', atomic_mass: 270, can_combine: true, description: 'A synthetic element.', x: 7, y: 7 },
    { atomic_number: 108, symbol: 'Hs', name: 'Hassium', type: 'transition_metal', atomic_mass: 269, can_combine: true, description: 'A synthetic element.', x: 8, y: 7 },
    { atomic_number: 109, symbol: 'Mt', name: 'Meitnerium', type: 'transition_metal', atomic_mass: 278, can_combine: true, description: 'A synthetic element.', x: 9, y: 7 },
    { atomic_number: 110, symbol: 'Ds', name: 'Darmstadtium', type: 'transition_metal', atomic_mass: 281, can_combine: true, description: 'A synthetic element.', x: 10, y: 7 },
    { atomic_number: 111, symbol: 'Rg', name: 'Roentgenium', type: 'transition_metal', atomic_mass: 282, can_combine: true, description: 'A synthetic element.', x: 11, y: 7 },
    { atomic_number: 112, symbol: 'Cn', name: 'Copernicium', type: 'transition_metal', atomic_mass: 285, can_combine: true, description: 'A synthetic element.', x: 12, y: 7 },
    { atomic_number: 113, symbol: 'Nh', name: 'Nihonium', type: 'post_transition_metal', atomic_mass: 286, can_combine: true, description: 'A synthetic element.', x: 13, y: 7 },
    { atomic_number: 114, symbol: 'Fl', name: 'Flerovium', type: 'post_transition_metal', atomic_mass: 289, can_combine: true, description: 'A synthetic element.', x: 14, y: 7 },
    { atomic_number: 115, symbol: 'Mc', name: 'Moscovium', type: 'post_transition_metal', atomic_mass: 289, can_combine: true, description: 'A synthetic element.', x: 15, y: 7 },
    { atomic_number: 116, symbol: 'Lv', name: 'Livermorium', type: 'post_transition_metal', atomic_mass: 293, can_combine: true, description: 'A synthetic element.', x: 16, y: 7 },
    { atomic_number: 117, symbol: 'Ts', name: 'Tennessine', type: 'halogen', atomic_mass: 294, can_combine: true, description: 'A synthetic element.', x: 17, y: 7 },
    { atomic_number: 118, symbol: 'Og', name: 'Oganesson', type: 'noble_gas', atomic_mass: 294, can_combine: false, description: 'A synthetic element.', x: 18, y: 7 },
];

const compoundRecipes = [
    { name: 'Water', formula: 'H₂O', elements: [{ symbol: 'H', count: 2 }, { symbol: 'O', count: 1 }], description: 'The universal solvent and a necessity for all known life.' },
    { name: 'Carbon Dioxide', formula: 'CO₂', elements: [{ symbol: 'C', count: 1 }, { symbol: 'O', count: 2 }], description: 'A gas exhaled by animals and absorbed by plants during photosynthesis.' },
    { name: 'Table Salt', formula: 'NaCl', elements: [{ symbol: 'Na', count: 1 }, { symbol: 'Cl', count: 1 }], description: 'An ionic compound essential for human health and widely used as a food seasoning.' },
    { name: 'Methane', formula: 'CH₄', elements: [{ symbol: 'C', count: 1 }, { symbol: 'H', count: 4 }], description: 'A powerful greenhouse gas and the main component of natural gas.' },
    { name: 'Ammonia', formula: 'NH₃', elements: [{ symbol: 'N', count: 1 }, { symbol: 'H', count: 3 }], description: 'A compound of nitrogen and hydrogen, used in cleaning products and fertilizers.' },
    { name: 'Sulfuric Acid', formula: 'H₂SO₄', elements: [{ symbol: 'H', count: 2 }, { symbol: 'S', count: 1 }, { symbol: 'O', count: 4 }], description: 'A strong mineral acid widely used in industry.' },
    { name: 'Hydrogen Peroxide', formula: 'H₂O₂', elements: [{ symbol: 'H', count: 2 }, { symbol: 'O', count: 2 }], description: 'A mild antiseptic and bleaching agent.' },
    { name: 'Baking Soda', formula: 'NaHCO₃', elements: [{ symbol: 'Na', count: 1 }, { symbol: 'H', count: 1 }, { symbol: 'C', count: 1 }, { symbol: 'O', count: 3 }], description: 'Sodium bicarbonate, a common leavening agent used in baking.' },
];

const findCompound = (mixZone) => {
    const mixedElements = mixZone.reduce((acc, element) => {
        acc[element.symbol] = (acc[element.symbol] || 0) + 1;
        return acc;
    }, {});

    for (const recipe of compoundRecipes) {
        const recipeElements = recipe.elements.reduce((acc, el) => {
            acc[el.symbol] = el.count;
            return acc;
        }, {});

        const symbolsMatch = Object.keys(mixedElements).every(symbol => recipeElements[symbol] === mixedElements[symbol]);
        const countsMatch = Object.keys(recipeElements).every(symbol => recipeElements[symbol] === mixedElements[symbol]);

        if (symbolsMatch && countsMatch) {
            return recipe;
        }
    }
    return null;
};

// Component for a single element on the periodic table
const ElementCard = ({ element, onClick, isDraggable, onDragStart, isLitUp }) => (
    <motion.div
        className={`
            relative p-2 m-1 w-16 h-16 flex flex-col justify-center items-center text-center text-xs font-bold rounded-lg
            transition-all duration-300 transform
            shadow-md
            ${isLitUp ? 'bg-indigo-400/80 hover:bg-indigo-400 ring-4 ring-indigo-300 ring-offset-2 ring-offset-gray-900' : 'bg-gray-700 hover:bg-gray-600'}
            ${isDraggable ? 'cursor-grab active:cursor-grabbing' : 'cursor-pointer'}
        `}
        style={{
            minWidth: '4rem',
            minHeight: '4rem',
            gridColumnStart: element.x,
            gridRowStart: element.y
        }}
        onClick={() => onClick(element)}
        draggable={isDraggable}
        onDragStart={(e) => onDragStart(e, element)}
        whileHover={{ scale: 1.1, zIndex: 10 }}
        whileTap={{ scale: 0.95 }}
    >
        <span className="text-white text-xs absolute top-1 left-2">{element.atomic_number}</span>
        <span className="text-white text-xl font-extrabold">{element.symbol}</span>
        <span className="text-white text-xs absolute bottom-1">{element.name}</span>
    </motion.div>
);

// Component for the information panel
const InfoPanel = ({ selectedElement, currentCompound, onReset }) => {
    return (
        <div className="bg-gray-800 p-6 rounded-lg shadow-lg text-white flex-1 min-w-[300px] max-w-[400px] h-full flex flex-col">
            <h2 className="text-3xl font-extrabold mb-4 text-center text-indigo-400">Information</h2>
            <div className="flex-grow overflow-y-auto">
                {selectedElement && !currentCompound && (
                    <motion.div
                        key={selectedElement.symbol}
                        initial={{ opacity: 0, y: 20 }}
                        animate={{ opacity: 1, y: 0 }}
                        exit={{ opacity: 0, y: -20 }}
                        transition={{ duration: 0.3 }}
                    >
                        <h3 className="text-2xl font-bold mb-2">{selectedElement.name} <span className="text-gray-400">({selectedElement.symbol})</span></h3>
                        <p className="text-sm">Atomic Number: <span className="font-semibold">{selectedElement.atomic_number}</span></p>
                        <p className="text-sm">Atomic Mass: <span className="font-semibold">{selectedElement.atomic_mass}</span></p>
                        <p className="text-sm mb-4">Type: <span className="font-semibold capitalize">{selectedElement.type.replace('_', ' ')}</span></p>
                        <p className="text-gray-300">{selectedElement.description}</p>
                    </motion.div>
                )}

                {currentCompound && (
                    <motion.div
                        key={currentCompound.formula}
                        initial={{ opacity: 0, y: 20 }}
                        animate={{ opacity: 1, y: 0 }}
                        exit={{ opacity: 0, y: -20 }}
                        transition={{ duration: 0.3 }}
                    >
                        <h3 className="text-2xl font-bold mb-2">Compound Formed!</h3>
                        <p className="text-4xl font-extrabold text-indigo-400 mb-2">{currentCompound.formula}</p>
                        <p className="text-xl font-semibold mb-4">{currentCompound.name}</p>
                        <p className="text-gray-300">{currentCompound.description}</p>
                        <motion.button
                            className="w-full mt-6 px-4 py-2 bg-indigo-500 hover:bg-indigo-600 text-white font-bold rounded-lg shadow-lg transition-all duration-300"
                            onClick={onReset}
                            whileHover={{ scale: 1.05 }}
                            whileTap={{ scale: 0.95 }}
                        >
                            Reset
                        </motion.button>
                    </motion.div>
                )}

                {!selectedElement && !currentCompound && (
                    <div className="text-center text-gray-400 text-lg flex-grow flex items-center justify-center">
                        <p>Click on an element to see its details, or drag one to the mix zone!</p>
                    </div>
                )}
            </div>
        </div>
    );
};

// Main App component
const App = () => {
    const [selectedElement, setSelectedElement] = useState(null);
    const [mixZoneElements, setMixZoneElements] = useState([]);
    const [currentCompound, setCurrentCompound] = useState(null);

    // This single function will handle the full game reset
    const handleFullReset = () => {
        setSelectedElement(null);
        setMixZoneElements([]);
        setCurrentCompound(null);
    };

    const handleElementClick = (element) => {
        setSelectedElement(element);
    };

    const handleDragStart = (e, element) => {
        e.dataTransfer.setData("element", JSON.stringify(element));
    };

    const handleDragOver = (e) => {
        e.preventDefault();
    };

    const handleDrop = (e) => {
        e.preventDefault();
        const element = JSON.parse(e.dataTransfer.getData("element"));

        if (element) {
            setMixZoneElements((prev) => [...prev, element]);
        }
    };

    useEffect(() => {
        if (mixZoneElements.length > 0) {
            const compound = findCompound(mixZoneElements);
            if (compound) {
                setCurrentCompound(compound);
                setSelectedElement(null);
            }
        }
    }, [mixZoneElements]);

    // Logic to determine which elements should be lit up
    const getLitUpElements = (currentMix) => {
        if (currentCompound) return [];

        const mixSymbols = currentMix.map(el => el.symbol);
        const nextPossibleSymbols = new Set();

        for (const recipe of compoundRecipes) {
            const recipeSymbols = recipe.elements.map(el => el.symbol);

            const allMixSymbolsPresentInRecipe = mixSymbols.every(symbol => recipeSymbols.includes(symbol));
            if (allMixSymbolsPresentInRecipe) {
                const isRecipeComplete = mixSymbols.length === recipeSymbols.length;
                if (!isRecipeComplete) {
                    recipeSymbols.forEach(symbol => {
                        const countInMix = mixSymbols.filter(s => s === symbol).length;
                        const countInRecipe = recipe.elements.find(e => e.symbol === symbol).count;
                        if (countInMix < countInRecipe) {
                            nextPossibleSymbols.add(symbol);
                        }
                    });
                } else if (findCompound(currentMix)) {
                    const compound = findCompound(currentMix);
                    if (compound) return [];
                }
            }
        }
        
        if (mixSymbols.length === 0) {
          return elementsData.filter(el => el.can_combine).map(el => el.symbol);
        }
        
        return Array.from(nextPossibleSymbols);
    };

    const litUpSymbols = getLitUpElements(mixZoneElements);

    return (
        <div className="bg-gray-900 min-h-screen text-white font-inter flex flex-col p-4 md:p-8">
            <h1 className="text-4xl md:text-5xl font-extrabold text-center mb-6 text-indigo-400">TedBi Periodic Table Game</h1>
            <p className="text-center text-sm md:text-base text-gray-300 mb-8">
                Drag elements to the "Mix Zone" to create new compounds!
            </p>

            <div className="flex flex-col md:flex-row gap-8 flex-grow">
                {/* Main Game Area */}
                <div className="flex-1 flex flex-col gap-4">
                    <motion.button
                        className="w-full px-6 py-3 bg-red-500 hover:bg-red-600 text-white font-bold rounded-lg shadow-lg transition-all duration-300"
                        onClick={handleFullReset}
                        whileHover={{ scale: 1.05 }}
                        whileTap={{ scale: 0.95 }}
                    >
                        Reset Game
                    </motion.button>
                    {/* Periodic Table Grid */}
                    <div className="grid grid-cols-18 grid-rows-[repeat(7,minmax(0,1fr))_0.5rem_repeat(2,minmax(0,1fr))] gap-1 w-full justify-center">
                        {elementsData.map((element) => (
                            <ElementCard
                                key={element.symbol}
                                element={element}
                                onClick={handleElementClick}
                                isDraggable={litUpSymbols.includes(element.symbol)}
                                onDragStart={handleDragStart}
                                isLitUp={litUpSymbols.includes(element.symbol)}
                            />
                        ))}
                    </div>

                    {/* Mix Zone */}
                    <div
                        className="w-full min-h-[150px] bg-gray-800 border-4 border-dashed border-indigo-500 rounded-xl mt-4 p-4 flex flex-wrap gap-2 items-center justify-center transition-all duration-300"
                        onDragOver={handleDragOver}
                        onDrop={handleDrop}
                    >
                        <AnimatePresence>
                            {mixZoneElements.length > 0 ? (
                                mixZoneElements.map((el, index) => (
                                    <motion.div
                                        key={`${el.symbol}-${index}`}
                                        initial={{ opacity: 0, scale: 0.5 }}
                                        animate={{ opacity: 1, scale: 1 }}
                                        exit={{ opacity: 0, scale: 0.5 }}
                                        transition={{ duration: 0.2 }}
                                        className="p-3 bg-indigo-500 rounded-full text-white font-bold text-xl shadow-lg"
                                    >
                                        {el.symbol}
                                    </motion.div>
                                ))
                            ) : (
                                <p className="text-gray-400 text-lg">Drag elements here to mix them!</p>
                            )}
                        </AnimatePresence>
                    </div>
                </div>

                {/* Information Panel */}
                <InfoPanel selectedElement={selectedElement} currentCompound={currentCompound} onReset={handleFullReset} />
            </div>
        </div>
    );
};

// The root for rendering the app
document.addEventListener('DOMContentLoaded', () => {
    // We've replaced the modern createRoot with the classic render method for broader compatibility.
    ReactDOM.render(
        <React.StrictMode>
            <App />
        </React.StrictMode>,
        document.getElementById('root')
    );
});

// Load Tailwind CSS and the Inter font
const link1 = document.createElement('link');
link1.href = 'https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900&display=swap';
link1.rel = 'stylesheet';
document.head.appendChild(link1);

const script = document.createElement('script');
script.src = 'https://cdn.tailwindcss.com';
document.head.appendChild(script);

// Set up the root div for React
document.body.innerHTML = '<div id="root"></div>';

export default App;
