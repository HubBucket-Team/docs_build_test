.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">1</div></div>

   Download the binary files for the desired release of MongoDB.
   `````````````````````````````````````````````````````````````

   Download the binaries from the `MongoDB Download Center
   <https://www.mongodb.com/download-center#production>`_.
   

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 1: Download the binary files for the desired release of MongoDB.
   `````````````````````````````````````````````````````````````````````

   Download the binaries from the `MongoDB Download Center
   <https://www.mongodb.com/download-center#production>`_.
   

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">2</div></div>

   Extract the files from the downloaded archive.
   ``````````````````````````````````````````````

   For example, from a system shell, you can extract through the ``tar`` command:
   

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 2: Extract the files from the downloaded archive.
   ``````````````````````````````````````````````````````

   For example, from a system shell, you can extract through the ``tar`` command:
   

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">3</div></div>

   Copy the extracted archive to the target directory.
   ```````````````````````````````````````````````````

   Copy the extracted folder to the location from which MongoDB will run.
   

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 3: Copy the extracted archive to the target directory.
   ```````````````````````````````````````````````````````````

   Copy the extracted folder to the location from which MongoDB will run.
   

.. only:: html or dirhtml or singlehtml

   .. raw:: html
   
      <div class="sequence-block"><div class="bullet-block"><div class="sequence-step">4</div></div>

   Ensure the location of the binaries is in the ``PATH`` variable.
   ````````````````````````````````````````````````````````````````

   The MongoDB binaries are in the ``bin/`` directory of the archive. To
   ensure that the binaries are in your ``PATH``, you can modify your
   ``PATH``.
   

   For example, you can add the following line to your shell's
   ``rc`` file (e.g. ``~/.bashrc``):

   .. code-block:: sh
   
      export PATH=<mongodb-install-directory>/bin:$PATH
      

   Replace ``<mongodb-install-directory>`` with the path to the extracted
   MongoDB archive.
   

   .. raw:: html
   
      </div>

.. only:: not(html or dirhtml or singlehtml)

   Step 4: Ensure the location of the binaries is in the ``PATH`` variable.
   ````````````````````````````````````````````````````````````````````````

   The MongoDB binaries are in the ``bin/`` directory of the archive. To
   ensure that the binaries are in your ``PATH``, you can modify your
   ``PATH``.
   

   For example, you can add the following line to your shell's
   ``rc`` file (e.g. ``~/.bashrc``):

   .. code-block:: sh
   
      export PATH=<mongodb-install-directory>/bin:$PATH
      

   Replace ``<mongodb-install-directory>`` with the path to the extracted
   MongoDB archive.
   

