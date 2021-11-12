# Covid-Safe-ZoneApp
*จำเป็นต้องติดตั้ง*
expo install @react-navigation/native
expo install react-native-screens react-native-safe-area-context

*****************************************************************************
expo install @react-navigation/native-stack
expo install @react-navigation/bottom-tabs

*****************************************************************************
*ใช้ Drawer ต้องติดตั้ง Gesture ด้วย*
expo install @react-navigation/drawer
expo install react-native-gesture-handler react-native-reanimated

*****************************************************************************
ถ้า install ก่อนหน้าแล้ว Error ใชัอันนี้
expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view

*****************************************************************************
expo install @expo/vector-icons

import { NavigationContainer } from "@react-navigation/native";
import { createNativeStackNavigator } from "@react-navigation/native-stack";
import { createBottomTabNavigator } from "@react-navigation/bottom-tabs";
import { createDrawerNavigator } from "@react-navigation/drawer";
