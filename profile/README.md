<h1 align=center> OSTIS Project </h1>

<p align="center">
  <b>OSTIS</b> (Open Semantic Technology for Intelligent Systems) is an open-source technology for the <b>compatible intelligent systems of the new generation</b> design. <br>

</p>

## Rationale

**Intelligent system** is not a system that is able to solve a specific problem, but a system that can easily learn how to solve new problems without significant costs.

To create an intelligent system, we need to integrate various types of knowledge and various problem-solving models and use intelligent interfaces, since it's unknown which set of models and knowledge will be necessary to solve a specific class of problems.
<p align="center">
<table>
  <tr>
    <td>Various types of knowledge</td>
    <td>Various problem solving models</td>
  </tr>
  <tr>
    <td>
    <ul>
      <li>facts</li>
      <li>logical statements</li>
      <li>situations</li>
      <li>events</li>
      <li>algorithms</li>
      <li>etc.</li>
    </ul>
    </td>
    <td>
      <ul>
         <li>logical models</li>
         <li>statistical models</li>
         <li>neural networks</li>
         <li>classical algorithms and genetic algorithms</li>
         <li>etc.</li>
      </ul>
    </td>
  </tr>
 </table>
</p>

There are systems that partially solve the problem of such an integration (hybrid intelligent systems), but currently they have several disadvantages:

- Such systems are made monolithic, so they are very difficult to modify
- It is practically impossible to reuse such systems (or components of such systems) to solve problems of a completely different class; you have to develop all the components anew.
- The development of such systems costs enormous resources.

It's not hard to notice that the main problem is expandability of such systems. Thus, we need a technology to design intelligent systems that are compatible with each other, because interaction between intelligent systems is one of the ways to enable intelligent systems to solve new classes of problems. OSTIS is a technology to create **semantically compatible** intelligent systems.

## Principles

### **SC-code**

The OSTIS Technology is based on a universal way to represent information, named SC-code (Semantic Computer Code). The SC-code is based on the basic formalisms of discrete mathematics (set theory and graph theory).

That ensures:

- **Universality** and **uniformity** of information representation (any information can be represented in the same way).

- The convenience of machine processing and human perception.

The SC-code is a **standard** for universal sense representation of information in the memory of computer systems.

SC-code features:

- The SC-code is non-linear, so it can be used to encode information in the memory of semantic associative computers.
- The basic alphabet of the SC-code consists of only 5 elements, on the basis of which more and more complex structures are built.
- You can use the SC-code to represent not only the knowledge of the system but also the problem-solving models and system interface.
- The SC-code is abstract language and can be visualized in different forms. Currently, there are several forms of the SC-code: SCg-, SCn-, SCs-code.

<p align="center">
  <img src="https://github.com/ostis-ai/.github/blob/main/profile/scg-logic-rule.jpeg?raw=true"/>
</p>

*Simple logic rule represented in the SCg-code: "If X is a bird, then X is an animal"*

### **Architecture**

Every ostis-based system (referenced as ostis-system down the line for convenience) consists of the following components:

- A knowledge base of ostis-system: can describe any kind of knowledge, easy to supplement with new knowledge types.

- A problem solver of ostis-system: based on a multi-agent approach, allows integrating and combining any problem-solving models.

- A user interface of the ostis-system: a special kind of knowledge base and problem solver, i.e. is also described by means of the SC-code.

## Advantages

- **Any** problem-solving model or knowledge can be seamlessly integrated into **any** ostis-system without **any** overhead costs (by the plug & play principle). Thus, it does not matter what the system can do at the moment: it can always be retrained to solve another problem

- Existing components of ostis-systems are universal (they can be used in completely different systems) and are compatible with each other. Thus, it is possible to accumulate a library of components and reuse components, greatly reducing the system evolution laboriousness.

- Due to the fact that the entire system is described by means of the SC-code, it can analyze itself, look for errors in itself and optimize its own work, i.e. has reflexivity. Reflexivity is considered one of the key signs of **intelligence**.

- Due to the presence of the basic alphabet of the SC-code and the possibility of a complete description of the system by means of the SC-code, it becomes possible to make ostis-systems completely platform-independent. That is, the development of an ostis-system comes down to the development of its model. The platform, in turn, can be implemented both in software (like a virtual machine) and in hardware.

- OSTIS is the basis for a new type of computers – semantic computers. Uncommon computers with unconventional architecture (including supercomputers) are often difficult to use due to the lack of software. The OSTIS Technology and ostis-systems will run on semantic computers, easing the migration to the next generation of computers.

- Due to the special kind of multi-agent information processing used in OSTIS, ostis-systems are initially focused on parallel processing of information (including its support at the hardware level within a semantic computer).

## Key takeaways

OSTIS is not a specific intelligent system or a method for solving problems of any class; it is a **technology** for developing intelligent systems, each of which, in turn, will solve problems of a certain class.

The key advantages of OSTIS lie not in fundamentally new functional capabilities of the systems being developed (most ostis-systems features can be implemented with traditional tools), but in how easy it is to modify and develop the systems, adapt them to new tasks as well as how efficiently it is possible to accumulate and use the obtained components in the development of new systems, while reducing the time and labor intensity of the development process.

OSTIS is a way to solve the compatibility problem, one of the most important problems of modern technologies.

## List of repositories developed by the project

- [Basic tools for ostis-system development](https://github.com/ostis-ai)
  - [OSTIS Standard](https://github.com/ostis-ai/ostis-standard)
  - [OSTIS Metasystem](https://github.com/ostis-ai/ims.ostis.kb)
  - [OSTIS Platform](https://github.com/ostis-ai/ostis-web-platform)
    - [Software implementation of sc-memory](https://github.com/ostis-ai/sc-machine)
    - [Python API client](https://github.com/ostis-ai/py-sc-client)
    - [TypeScript API client](https://github.com/ostis-ai/ts-sc-client)
    - [Software implementation of scp-machine](https://github.com/ostis-ai/scp-machine)
    - [Software implementation of interpreter of user interface sc-models](https://github.com/ostis-ai/sc-web)
    - [Component manager for ostis-systems](https://github.com/ostis-ai/sc-component-manager)
  - [Knowledge Base source Editor](https://github.com/ostis-ai/kbe)
  - [Plugin for Visual Studio code](https://github.com/ostis-dev/vs-code-ostis)

- [Applications built on top of the OSTIS Technology](https://github.com/ostis-apps)

## Fast start

Go to [OSTIS Web-oriented software platform](https://github.com/ostis-ai/ostis-web-platform) and read README to father instructions.

## More information

More about OSTIS you can read [here](https://libeldoc.bsuir.by/handle/123456789/51151).

[![](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCjSsaMx_DmA_LEnG4Rzadpw)
