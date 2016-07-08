---
layout:     post
title:      "主流数据库常见操作接口"
date:       2016-07-01 12:00:00
author:     "Hux"
header-img: ""
tags:
    - Activejdbc
    - 数据库
    - Java
---


> [项目链接](https://github.com/teclan/declan-activejdbc)


<div>
    <blockquote>主流数据库常见操作……
        <br>Oracle9i+,SqlServer2k+,mysql5.6+,DB28.5+,达梦7+，金仓</blockquote>
  <br>
  <br><b>  提供常见操作支持
  <br>
  <br><b> String getDriverClass();
  <br>
  <br><b> String getUrlTemplate();
  <br>
  <br><b> ArrayList<String> getTables() throws SQLException;
  <br>
  <br><b> boolean hasTable(String tableName);
  <br>
  <br><b> boolean openDatabase();
  <br>
  <br><b> void closeDatabase();
  <br>
  <br><b> boolean openDatabase(String name);
  <br>
  <br><b> void closeDatabase(String name);
  <br>
  <br><b> boolean hasConnected();
  <br>
  <br><b> boolean hasConnected(String name);
  <br>
  <br><b> boolean Triggerexists(String tableName, String action);
  <br>
  <br><b> void createTrigger(String tableName);
  <br>
  <br><b> void removeTrigger(String tableName);
  <br>
  <br><b> void createEventTable();
  <br>
  <br><b> void dropEventTable();
  <br>
  <br><b> DbType getDbType();
  <br>
  <br><b> void retrieve(String table);
  <br>
  <br><b> void retrieveWithoutAdapter(String table, String action, String[] pkNames, Object[] newPkValues, Object[] oldPkValues);
  <br>
  <br><b> void retrieve(String table, String action, String[] pkNames,Object[] newPkValues, Object[] oldPkValues);
  <br>
  <br><b> Map<String, String> getTableColumns(String tableName);
  <br>
  <br><b> List<String> getPkNames(String table);
  <br>
  <br><b> void execute(String sql);
  <br>
  <br><b> void execute(String name, String sql);
  <br>
  <br><b> void execute(File file);
  <br>
  <br><b> void execute(String name, File file);
</div>
