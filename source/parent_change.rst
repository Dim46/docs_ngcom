.. _ngcom_parent_change:

Как перемещать ресурсы внутри Веб ГИС
======================================

Ресурсы :ref:`Веб ГИС <ngcom_description>` (слои, соединения, сервисы, группы) можно перемещать из одной :ref:`Группы ресурсов <ngcom_resources_group>` в другую и после их создания. Для этого:

#. Откройте окно свойств ресурса, который вы хотите переместить;
#. Выберите :menuselection:`Действие --> Изменить` на правой панели :ref:`веб-интерфейса <ngw_admin_interface>` Веб ГИС;
#. В открывшемся окне через меню :guilabel:`Родитель` на вкладке :guilabel:`Ресурс` выберите Группу ресурсов, в которую вы хотите переместить свой ресурс;
#. Нажмите кнопку :guilabel:`Сохранить`. Если ресурс успешно перемещен, то информация о нем появится в новой Группе ресурсов и пропадет в старой Группе ресурсов.

Аналогичным образом между родительскими ресурсами (:ref:`Векторными слоями <ngcom_vector_layer>`, :ref:`Растровыми слоями <ngcom_raster_layer>`, :ref:`Слоями PostGIS <ngcom_postgis_layer>`) можно перемещать :ref:`Стили <ngcom_styles>`.
