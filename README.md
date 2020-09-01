# PERTURBO Workshop Practice Handout  

[TOC]

## Practice 0: Syntax Examples



**Goal:** short description of the Practice goal
### Subsections (if needed)

Equation example:
$$E=Q_{ati}^{on}$$

In-line equation example: $E=Q_{ati}^{on}$

Link example: [perturbo](https://perturbo-code.github.io)

> Quote example 

List example:
- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item

Some `inline code` here. 

```bash=
#some bash code here
cd ~
cp file.dat file2.dat
```

```python=
#some Python code here
if python is needed_here_at_all:
    print('Hello')
```

:file_folder: `this is a directory`

:page_facing_up: `this is a file`

## Practice 1: Perturbo Download and Installation 
> [name=itelu] [time=Mon, Aug 31, 2020] 

#### How to install Quantum Espresso?
```bash=
>> wget <quantum espresso package>
>> make pw ph pp
```

#### How to install Wannier90?


#### How to install PERTURBO?

Please change into the Quantum Espresso directory and download the PERTURBO codes
```bash=
>> git clone https://github.com/perturbo-code/perturbo.git
```

#### Recommended directory hierarchy
 
- :open_file_folder: **pw-ph-wan**
  - :file_folder: scf
  - :file_folder: nscf
  - :file_folder: phonon
  - :file_folder: wann
- :file_folder: **qe2pert**
- :open_file_folder: **perturbo**
  - :file_folder: pert-band
  - :file_folder: pert-setup
  - :face_with_monocle: .........







## Practice 2: Preliminary Steps
> [name=Jinsoo]


## Practice 3: Charge Transport Calculation
> [name=Jin-Jian]


## Practice 4: Ultrafast Dynamics in the BTE framework
> [name=Ivan]